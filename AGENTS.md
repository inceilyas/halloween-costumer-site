# halloween-costumer-site

Single source of instructions; `CLAUDE.md` only contains `@AGENTS.md`. Make changes here.

## Purpose
Static legal and support site for the iOS app "Halloween Costumer": home, Privacy Policy, Terms of Use, Support. Published with GitHub Pages from the root of `main`. The app and App Store Connect link to the English pages, so those URLs must not change (`/`, `/privacy.html`, `/terms.html`, `/support.html`). The other languages live under `/<lang>/` with the same four pages.

## Rules
- Never use emoji, in any output (pages, comments, commit messages, docs).
- 11 languages: English (source, served from the root) and tr, de, fr, it, es, pt-br, ru, ja, ko, zh-hant (folders `/tr/`, `/de/`, ...). English is the legal source: every non-English privacy and terms page carries a note that the English version prevails. Change the English text first, then update every translation (a structural parity check in `check.py` catches dropped or added blocks).
- Language switcher is a `<details>` menu (no JavaScript) plus a footer list; every page has `hreflang` links for all languages and `x-default` (English).
- No tracking: no cookies, no analytics, no external resources (no CDNs, no web fonts from a server). Fonts are self-hosted under `assets/fonts` with their OFL license. The Bungee subset is Latin only; page titles in ru, ja, ko and zh-hant use a system font (see `assets/style.css`).
- Do not promise features that are not shipped in the app (video generation is not in version 1.0).
- Keep the text consistent with the app repo (`halloween-photo-app`, `docs/store/privacy-policy.md`, `terms-of-use.md`, `support-page.md`) and with the App Privacy answers in App Store Connect. A change in one place means a change in all.
- Names, contact data and the effective date live only in `config.env`. Page text lives in `src/<lang>/privacy.md`, `terms.md`, `support.md` and `index.html` (`src/en/` is the source). Effective dates are per language: `EFFECTIVE_DATE_<KEY>`. Never edit the generated `*.html` files at the root by hand.
- Do not commit or push without the owner's approval.

## Workflow
1. Edit `config.env` or a file in `src/<lang>/`.
2. `python3 build.py` regenerates all pages (`python3 build.py de` builds one language).
3. `python3 check.py` verifies links, anchors, canonical URLs, hreflang, language switcher, the conflict note, structural parity with English, tags, tokens, emoji and external resources. Use `python3 check.py --strict` before publishing: it fails while open `[PLACEHOLDER]` decisions remain in the text.
4. Commit the sources and the generated pages together.

## Design
"Hayalet Treni" palette from the app (`docs/ui-spec.md`): pit black background, ticket cream text, bulb yellow links, ghost turquoise sparingly. System fonts for text, Bungee for headings only. Contrast at least 4.5:1, visible keyboard focus, skip link, mobile first.

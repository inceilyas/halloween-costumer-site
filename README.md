# halloween-costumer-site

Static legal and support pages for the iPhone app Halloween Costumer: home, Privacy Policy, Terms of Use and Support. English plus ten translations. No cookies, no analytics, no external resources.

## Files

| Path | Purpose |
| --- | --- |
| `index.html`, `privacy.html`, `terms.html`, `support.html` | Generated English pages at the root (served by GitHub Pages; do not edit by hand) |
| `tr/`, `de/`, `fr/`, `it/`, `es/`, `pt-br/`, `ru/`, `ja/`, `ko/`, `zh-hant/` | Generated translations, same four pages each |
| `src/<lang>/index.html` | Home page fragment (`src/en/` is the source language) |
| `src/<lang>/privacy.md`, `terms.md`, `support.md` | Page text in Markdown |
| `src/layout.html` | Shared page template (header, navigation, footer) |
| `config.env` | `APP_NAME`, `SUPPORT_EMAIL`, `DEVELOPER_NAME`, `SITE_URL`, `YEAR`, `EFFECTIVE_DATE_<KEY>` per language |
| `build.py`, `check.py` | Build and check scripts (Python 3 standard library only) |
| `assets/style.css`, `assets/favicon.svg` | Styles and icon |
| `assets/fonts/` | Bungee (SIL Open Font License) subset for headings, with its license |
| `.nojekyll` | Turns off Jekyll processing on GitHub Pages; keep it |

## Rebuild

```sh
python3 build.py     # regenerates every language from src/ and config.env (python3 build.py de = one language)
python3 check.py     # links, anchors, canonical, hreflang, switcher, conflict note, parity with English, tags, tokens, emoji, external resources
```

Use `python3 check.py --strict` before publishing. It fails while open decisions written in square brackets (for example `[UPGRADE_RULE]`, `[GOVERNING_STATE]`, `[24]`, `[2 business days]`) remain in the text. The build prints the same list as warnings.

Languages: English (root, the legal source), Turkish `/tr/`, German `/de/`, French `/fr/`, Italian `/it/`, Spanish `/es/`, Brazilian Portuguese `/pt-br/`, Russian `/ru/`, Japanese `/ja/`, Korean `/ko/`, Traditional Chinese `/zh-hant/`. Non-English privacy and terms pages say the English version prevails. To add a language: add a row to `LANGS` and `UI` in `build.py`, add `EFFECTIVE_DATE_<KEY>` to `config.env`, and translate the four files of `src/en/` into `src/<folder>/`.

Where to change things:

- Name, e-mail, effective dates, site URL: `config.env`, then rebuild.
- Wording: the English file in `src/en/` first, then every translation, then rebuild. Keep the app repo documents (`docs/store/*.md` in `halloween-photo-app`) and App Store Connect in sync.

## Publish with GitHub Pages

1. Create a public GitHub repository named `halloween-costumer-site` (the free Pages plan needs a public repository) and push `main`.
2. Settings > Pages > Build and deployment > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. After a minute or two the site is live at `https://inceilyas.github.io/halloween-costumer-site/`.

URLs used by the app and App Store Connect:

- Privacy Policy: `https://inceilyas.github.io/halloween-costumer-site/privacy.html`
- Terms of Use: `https://inceilyas.github.io/halloween-costumer-site/terms.html`
- Support: `https://inceilyas.github.io/halloween-costumer-site/support.html`
- Marketing: `https://inceilyas.github.io/halloween-costumer-site/`
- Translations: the same file names under `/tr/`, `/de/`, `/fr/`, `/it/`, `/es/`, `/pt-br/`, `/ru/`, `/ja/`, `/ko/`, `/zh-hant/`

The same addresses are in `AppConfig.swift` (`privacyURL`, `termsURL`) in the app repo.

## Before publishing

- `python3 check.py --strict` passes (no open placeholders).
- Texts match the shipped app (credits, prices, retention, deletion, no video in 1.0) and the App Privacy answers.
- A lawyer review of the privacy policy and terms is recommended; none has been done.

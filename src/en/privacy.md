title: Privacy Policy
description: How {{APP_NAME}} handles your photos and data: what is sent to the AI service, legal bases, what is stored and for how long, and your rights worldwide.

# Privacy Policy

> Effective date: {{EFFECTIVE_DATE}}

{{APP_NAME}} (the "App") turns your photos into Halloween monster portraits using a third-party AI image service. This policy explains what information the App handles, why and on what legal basis, who receives it, how long it is kept, and what rights and choices you have, wherever you live. The App is operated by {{DEVELOPER_NAME}} ("we", "us"), the controller of your personal data (the party that decides how and why it is processed). Our contact details are in section 14.

## 1. The short version

- Photos you choose are sent to an outside AI service (OpenAI) only to create the portrait you asked for. We ask for your clear permission before the first time this happens, and you can withdraw it at any time.
- We do not keep the photos you send. We forward them, in memory, to the AI service and send the result back to your phone. The App keeps a resized copy of the original only on your phone, for a before/after comparison (section 2c). Location data embedded in photos is not sent.
- Your finished portraits are saved on your phone. So that a portrait is not lost if your connection drops or the App is closed while it is being made, we keep a copy of each newly generated portrait, encrypted, on our server for at most 24 hours. It is used only to deliver the portrait to your phone, and it is deleted as soon as your phone confirms it was saved. Otherwise it is kept at most 24 hours, and an hourly cleanup removes it shortly after.
- We do not use your photos or your face to train AI models, for advertising, or for analytics. We do not identify or recognize people from their faces.
- There is no account, no advertising or analytics SDK in the App, and no tracking across other companies' apps and websites. Our server shares your anonymous ID and purchase records (never photos) with a subscription analytics provider (RevenueCat, section 4).
- You can delete your data from inside the App at any time (Profile > Delete all my data) and withdraw your AI consent (Profile > Withdraw AI consent).

## 2. Information we handle

**a. Photos you choose or take.** When you pick a photo from your library or take one with the camera, and tap to create a portrait, the photo (a resized JPEG) and the look you selected are sent to our backend and on to the AI service. If you choose a group or couple look with separate selfies, each selfie is sent. Photos can show the faces of you and of other people. We only access photos you explicitly choose; the App does not scan your photo library. Location data embedded in photos is not sent.

**b. Face check on your device.** Before a photo is sent, the App uses Apple's Vision framework on your device to check that a suitable number of faces is present (for example, exactly two for a couple look). This check runs entirely on your phone. It finds where faces are and how many there are. It does not create a face template or any biometric identifier, it does not identify or recognize who anyone is, and its results are not sent anywhere except as a face count used to write the instructions for the AI service. For a creation made from a single photo, the position of the face (a plain rectangle, normalized to the photo) is also kept in the creation's data on your phone only, to line up the before/after comparison (section 2c). The live camera guide also finds faces on your device while you frame the shot; this is not recorded or sent.

**c. Generated portraits.** The AI service's result comes back to the App and is saved on your phone. A temporary copy of each generated portrait is kept encrypted in our cloud storage, only to deliver it to your phone if the connection fails. It is deleted when your phone confirms it was saved; otherwise it is kept at most 24 hours, and an hourly cleanup removes it shortly after. We never store your selfies or other input photos on our servers. On your phone only, a creation made from a single photo (solo, or one group photo) also keeps a resized copy of the original photo (long edge 1280 pixels) next to the portrait, to show a before/after comparison. That copy is never uploaded, is excluded from your device backups, and is deleted with the creation or by Delete all my data. Creations made from separate selfies, and portraits recovered from our 24-hour delivery copy, have no original-photo copy. You can also make a short (about 4 second) before/after video from the original-photo copy and the portrait. It is created on your phone, saved to Photos or shared only when you tap Save video or Share video, and never uploaded to us. In addition, for every creation the App keeps a small thumbnail (about 256 pixels) of each input photo with the creation on your phone, including, for group creations made from separate selfies, the other people's photos, only to show the creation in the gallery. These thumbnails are never uploaded, are excluded from your device backups like the rest of the gallery, and are deleted with the creation or by Delete all my data. Portraits and their original-photo copies in the App's gallery are excluded from iCloud and device backups, so restoring a backup does not bring them back; save the portraits you want to keep to Photos.

**d. Anonymous identifier and credits.** The App creates an anonymous Firebase identifier for your installation. The sign-in for this identifier is stored in your iPhone's Keychain, so it usually stays on the device when you delete and reinstall the App on the same iPhone. iOS does not guarantee this; if the sign-in is gone, Restore Purchases (section 2e) moves your remaining subscription and pack credits back. The sign-in is removed when you use Delete all my data. We use it to keep your credit balance and to record purchases and credit movements (transaction ID, product, date). We also record each generation job (anonymous identifier, credit cost and timestamps; the selected look and the number of faces are removed as soon as a job finishes; technical logs contain a job number but not the selected look). We do not ask you to create an account and we do not collect your name, email address, or phone number in the App. When we call the AI service we include a pseudonymous identifier derived from your anonymous ID with a one-way hash; it is not your name, email or account ID, and it stays the same across your requests so the AI service can detect abuse. We also keep the date you last used the App (to apply the 24-month rule), short-lived rate-limit and content-filter counters, and a link between two anonymous IDs if you moved credits with Restore Purchases.

**e. Purchases.** Purchases and subscriptions are processed by Apple. We never receive your payment card or Apple Account details. We receive confirmation of a transaction (transaction ID, product, dates, renewal or refund status) so we can grant or remove credits. If you tap Restore Purchases, the App sends the purchase records that Apple has signed to our server so we can verify them and re-link your purchases and remaining credits to the App on this device. These records contain the product, dates and the random per-install purchase identifier we generated; they do not contain your name, email address or payment details. If the records match another install of the App, the remaining credits of that install are moved (not copied) to this one. Restore needs no sign-in and creates no new kind of personal data. We also pass these purchase records, together with your anonymous identifier, from our server to RevenueCat (section 4) so that we can see subscription and revenue statistics; the App itself contains no RevenueCat software and sends nothing to RevenueCat.

**f. Device integrity.** To protect the service from abuse, we use Apple's App Attest (through Firebase App Check) to confirm requests come from a genuine copy of the App, and Apple's DeviceCheck to remember, with a single on/off setting stored by Apple, that a device has already used its free first portrait. DeviceCheck does not tell us who you are. We do not store the device token.

**g. Technical logs.** Our cloud services and the AI service may log technical information such as IP address, request time, and error codes for security and to operate the service. Our own code does not intentionally write photos, face data or personal data into logs; platform logs may include your IP address and device type. We do not use these logs to build profiles about you.

**h. Messages to support.** If you email us, we receive your email address and what you write, and we use it only to reply.

**i. On-device settings.** The App stores simple preferences on your phone (for example, that you finished onboarding and that you agreed to the AI notice) and a few technical markers, such as already-saved result IDs and purchase IDs the server declined.

We do not collect your precise location, contacts, health data, or browsing history.

## 3. Why we use it, and legal bases

| Purpose | Information | Legal basis (GDPR and UK GDPR; equivalent bases under other laws) |
| --- | --- | --- |
| Create the portrait you ask for: send your photos and the chosen look to the AI service | Photos, selected look, face count, pseudonymous identifier | Your consent (Art. 6(1)(a)), given in the App before the first creation. You can withdraw it at any time; withdrawing does not affect earlier processing. |
| Credits, purchases, subscriptions, Restore Purchases, refunds of credits | Anonymous identifier, credit balance, purchase records | Performance of our contract with you (Art. 6(1)(b)); keeping records we must keep by law (Art. 6(1)(c)) |
| Understand subscriptions and revenue (subscription analytics) | Anonymous identifier, Apple-signed purchase and renewal records | Our legitimate interests in running and improving a paid service (Art. 6(1)(f)). You may object (section 7). |
| Prevent fraud and abuse, enforce the one free portrait per device, keep the service secure (App Check, DeviceCheck, rate limits, safety filters, logs) | Anonymous identifier, device integrity signals, technical logs | Our legitimate interests in protecting the service, other users and ourselves (Art. 6(1)(f)). You may object (section 7). |
| Answer support requests | Email address, message, Support ID | Our contract with you and our legitimate interest in helping you |
| Comply with law and handle legal claims | Records described in section 6 | Legal obligation and legitimate interests |

**Faces and photos.** Faces and photos in your pictures are used only to generate the portrait you requested. They are not used to train or improve any AI model, for advertising or marketing, for analytics or profiling, or sold or shared for those purposes. We do not build a database of faces, and we do not analyze photos to infer sensitive characteristics about anyone.

If you do not agree to send photos to the AI service, you can still open the App, but it cannot create portraits.

## 4. Who receives information

We share information only with the service providers needed to run the App:

- **OpenAI** (image generation). Your photos and the selected look are sent to OpenAI's API to produce your portrait. OpenAI acts as our processor. According to OpenAI's published API data policy, data sent to the API is not used to train or improve OpenAI's models unless the customer opts in (we have not opted in), and API content may be kept in abuse-monitoring logs for up to 30 days, or longer if required by law or needed to protect services. OpenAI's policy: https://developers.openai.com/api/docs/guides/your-data . OpenAI may also screen uploaded images for child sexual abuse material and keep a flagged image for review as described in that policy.
- **Google (Firebase and Google Cloud)** (backend hosting, anonymous identifier, credit and purchase records, app integrity checks, temporary encrypted storage of generated portraits). Google acts as our processor under its data processing terms. Our backend runs in the United States (Iowa).
- **RevenueCat, Inc.** (United States) (subscription and purchase analytics). Our server sends RevenueCat your anonymous identifier and the purchase records Apple has signed for your purchases (product, dates, environment, the random purchase identifier, and renewal, refund and cancellation events). RevenueCat acts as our processor. No photos, faces, names, email addresses or device identifiers are sent, and there is no RevenueCat software in the App. If sending a purchase record to RevenueCat fails, the signed purchase record and your anonymous ID wait in a temporary technical queue on our server for at most 3 days (section 6). When you use Delete all my data, we also ask RevenueCat to delete its record for your anonymous identifier.
- **Apple** (App Store purchases, App Attest, DeviceCheck, and optional sharing of your portraits and before/after videos via the iOS share sheet that you start yourself). Apple acts as an independent controller for its own services.
- **Authorities or successors**, when required by law or to protect rights and safety, or as part of a business transfer, with notice where required.

We do not sell your personal information, and we do not share it for cross-context behavioral advertising.

When you share a portrait or a before/after video to another app (for example from the share sheet), that app's own privacy policy applies to what you share.

## 5. International transfers

We are based in Türkiye, and our providers process data in the United States and possibly other countries where they operate. If you use the App in the European Economic Area, the United Kingdom, Switzerland, Türkiye, Brazil, South Korea, Japan or elsewhere, your information is therefore transferred to other countries, including countries whose data protection law may differ from yours.

We use the safeguards that your law requires for such transfers, where they apply: an adequacy decision (for example the EU-US Data Privacy Framework, where the recipient participates), standard contractual clauses (EU and the UK addendum) in our providers' data processing terms, other lawful mechanisms recognized by local law (see section 8), and your consent where the law allows it. We also limit what is sent to what is needed, use encrypted connections, and do not send your name, email address or real account identifier to the AI service. You can ask us for information about the safeguards (section 14).

## 6. How long we keep information

| Information | Retention |
| --- | --- |
| Photos sent for a creation | Not stored by us. Held in memory only while the request is processed. The AI service may keep them for up to 30 days in abuse-monitoring logs (see section 4). |
| Generated portraits and, for creations made from a single photo, the original-photo copy | On your phone until you delete them or use Delete all my data. The resized original-photo copy and its face rectangle never leave your phone. Portraits and original-photo copies in the App's gallery are excluded from iCloud and device backups, so restoring a backup does not bring them back. A temporary delivery copy of the portrait is kept encrypted on our server for at most 24 hours, and an hourly cleanup removes it shortly after (it is deleted when your phone confirms the save, and by Delete all my data). |
| Anonymous identifier, credit balance, credit movements, purchase records (including those used by Restore Purchases) | Until you delete your data in the App. Records with a zero balance, no active subscription and no use of the App for 24 months are deleted automatically (checked daily), together with the anonymous sign-in record. An unused free credit also counts as a balance. |
| Generation job records (anonymous identifier, credit cost and timestamps; the selected look and the number of faces are removed as soon as a job finishes) | Deleted automatically 30 days after completion, or earlier by Delete all my data. Jobs that never finished are deleted with your account or by the 24-month rule. |
| Record at RevenueCat (anonymous identifier, purchase and renewal records) | Until you delete your data in the App or the record is deleted automatically after 24 months of inactivity (see above); we then ask RevenueCat to delete it. RevenueCat's own terms govern any backup copies. |
| Temporary delivery queue to our subscription analytics provider (RevenueCat) | If sending a purchase record to RevenueCat (or, after you delete your data, the request to delete your record at RevenueCat) fails, the signed purchase record or request and your anonymous ID are kept in a technical queue for at most 3 days, then deleted. |
| Purchase transaction records after you delete your data in the App or after automatic deletion | Transaction ID, product and dates, and notification receipts without any identifier, are kept without any link to your anonymous identifier, to process refunds and avoid granting credits twice, and where law requires (for example for accounting). If you had an active subscription, the de-identified subscription record also keeps the remaining weekly credits of the current period. If you had unused credit packs, the de-identified purchase record of each pack transaction also keeps only the number of unused credits from that pack. These are stored only as numbers, without any link to your anonymous identifier and without any other data, so that you can restore them once with Restore Purchases, on a new install or on any install with the same Apple Account; they are used only for that, are returned only once, and are set to zero if Apple refunds that pack. Restore returns your unused paid credits; the free first credit is not restored, so in rare cases one paid credit may be missing. These records are kept for as long as accounting and refund rules require; we have not set a shorter deletion date. |
| Deletion marker | After you delete your data we keep your former random anonymous identifier and the deletion time, so that the deleted record cannot be re-created. It is kept indefinitely and contains only a random ID and a date. |
| Technical logs | A limited period needed for security and operations. Google Cloud technical logs are kept for 30 days by default (Firebase Authentication may keep IP addresses in its logs for a few weeks). |
| Free-portrait flag at Apple (DeviceCheck) | Kept by Apple, not by us. It holds no identity and is not reset by Delete all my data, so the free portrait cannot be claimed twice on the same device. |
| Support emails | As long as needed to help you, then deleted. |

## 7. Your rights and choices

Depending on where you live, you have some or all of these rights: to know whether we process your data and to get a copy (access); to correct it; to delete it; to restrict processing; to receive your data in a portable format; to object to processing based on legitimate interests; to withdraw consent at any time; not to be subject to decisions based solely on automated processing with legal or similarly significant effects (we make none); and to complain to a data protection authority.

How to use them:

- **Delete all my data (in the App).** Profile > Delete all my data removes the portraits, original photos, selfie thumbnails, and AI consent stored on your phone and asks us to delete the server-side record linked to your anonymous identifier (credit balance and purchase records), and asks RevenueCat to delete its record for that identifier. Your unused credit pack credits and the remaining weekly credits of an active subscription are not forfeited: only their number is kept with the de-identified purchase record (section 6), with no link to your anonymous identifier, so you can restore them once with Restore Purchases on a new install or on any install with the same Apple Account. Restore returns your unused paid credits; the free first credit is not restored, so in rare cases one paid credit may be missing. Deleting the App alone does not delete the server-side record.
- **Withdraw AI consent.** Profile > Withdraw AI consent. Photos will not be sent again until you agree again.
- **Access, portability, correction, restriction, objection.** Email {{SUPPORT_EMAIL}} and include the Support ID shown in the Profile tab, so we can find your record. We cannot look up your data without it, because the App is anonymous. We will send you the record linked to your Support ID (credit balance, credit movements and purchase records) in a common, machine-readable format. Your portraits are already on your phone.
- **Photo access.** You can change camera and photo permissions in iOS Settings. The App uses the system photo picker, which gives it access only to photos you select, and saves to your library only when you tap Save or Save video.
- **Subscriptions** are managed or cancelled in your Apple Account settings (see our Terms of Use).

We answer within one month (GDPR and UK GDPR; we may extend by up to two further months for complex requests and will tell you), or within the period set by the law that applies to you. We may ask you to confirm that a request comes from the owner of the Support ID. You can also complain to your local data protection authority (in the EEA, the authority of the country where you live or work; in the UK, the Information Commissioner's Office; in Türkiye, the Personal Data Protection Authority; in Brazil, the ANPD; in South Korea, the PIPC; in Japan, the PPC). We would appreciate the chance to resolve your concern first.

## 8. Information for specific regions

### 8.1 European Economic Area, United Kingdom and Switzerland

{{DEVELOPER_NAME}} is the controller. The legal bases are in section 3, transfers in section 5, retention in section 6, and your rights in section 7, including the rights to object and to withdraw consent. We have not appointed a data protection officer; privacy questions go to the address in section 14. Where the law of your country sets a higher age for consenting to the processing of personal data than 13 (for example 14 to 16 in several European countries), see section 9. The App is not currently offered in the EEA, the UK, mainland China or Thailand. If you use it from there anyway, we have not appointed a representative under Article 27 of the GDPR or the UK GDPR; you can contact us at the address in section 14.

### 8.2 Türkiye (Law No. 6698, KVKK)

{{DEVELOPER_NAME}} is the data controller. We process personal data for the purposes in section 3, on the grounds of your explicit consent (sending photos to the AI service), the establishment and performance of a contract, our legitimate interests (fraud prevention and security), and legal obligations. Under Article 11 of Law No. 6698 you may ask whether your data is processed, request information, learn the purpose and whether it is used appropriately, know the third parties to whom it is transferred in Türkiye or abroad, ask for correction or deletion, ask that these actions be notified to third parties, object to results against you, and claim compensation for damage. Apply to us at the address in section 14, with your Support ID; we answer within thirty days at the latest. If you are not satisfied, you may complain to the Personal Data Protection Board (KVKK). Data is transferred abroad (section 5) under the conditions of Article 9 of Law No. 6698.

### 8.3 Brazil (LGPD)

{{DEVELOPER_NAME}} is the controller and the contact for data subjects is the address in section 14. Our legal bases under Article 7 of Law No. 13.709/2018 are consent, performance of a contract, regular exercise of rights, and legitimate interests. You have the rights in Article 18 (confirmation of processing, access, correction, anonymization, blocking or deletion, portability, information about sharing, information about the consequences of refusing consent, and revocation of consent) and may petition the ANPD. International transfers are made as set out in section 5 and Article 33 of the LGPD.

### 8.4 South Korea (PIPA)

We process the personal information in section 2 only for the purposes in section 3 and keep it for the periods in section 6. We do not provide personal information to third parties other than as described in section 4. We entrust the processing described in section 4 to OpenAI, Google and RevenueCat, and we oversee them through contract terms. Your photos and related information are transferred overseas as follows, with your consent given in the App:

| Recipient and country | Items | Purpose | When and how | Retention |
| --- | --- | --- | --- | --- |
| OpenAI, United States | Photos, selected look, pseudonymous identifier | Generate the portrait | Each time you create a portrait, over an encrypted network | Up to 30 days in abuse-monitoring logs |
| Google (Firebase and Google Cloud), United States | Anonymous identifier, credit and purchase records, temporary copy of the generated portrait | Hosting, credit ledger, delivery of the portrait | Each time you use the App, over an encrypted network | As in section 6 |
| RevenueCat, United States | Anonymous identifier, purchase and subscription records | Subscription analytics | Each time a purchase, renewal or refund is processed, over an encrypted network | As in section 6 |

You may exercise your rights to access, correct, delete, suspend processing, and withdraw consent under PIPA by contacting us at the address in section 14; you may refuse consent, but then the App cannot create portraits. The person responsible for privacy is {{DEVELOPER_NAME}} ({{SUPPORT_EMAIL}}). You can also seek help from the Personal Information Protection Commission or the KISA Privacy Center (118).

### 8.5 Japan (APPI)

{{DEVELOPER_NAME}} is the business operator handling personal information. We use personal information only for the purposes in section 3. When you consent in the App, your photos and related information are provided to businesses in a foreign country: OpenAI and Google, in the United States and other countries where they operate. Your anonymous identifier and purchase records are also provided to RevenueCat in the United States. The United States has no single comprehensive personal information protection law like the APPI; our providers handle the data under their own commitments and contract terms described in section 4 (no training on API data, limited retention, encryption). You may request disclosure, correction, deletion and cessation of use of retained personal data, and a record of third-party provisions, by contacting us at the address in section 14.

### 8.6 United States

Depending on where you live (for example California, Colorado, Connecticut, Virginia, Texas, Oregon, and other states with consumer privacy laws), you may have the right to know what personal information we hold, access it, correct it, delete it, receive a portable copy, and appeal our decision. We do not sell personal information, do not share it for targeted advertising, and do not use it for profiling that has legal or similarly significant effects. We do not process photos to uniquely identify a person. To use these rights, use Delete all my data in the App or email {{SUPPORT_EMAIL}}; we will respond within 45 days (we may extend once where the law allows) and will not discriminate against you for exercising your rights. You may use an authorized agent; we may ask for the Support ID to verify the request. If we deny a request you may appeal by replying to our email, and you may contact your state attorney general.

California "Shine the Light" and Nevada requests can be sent to the same address. We do not respond to "Do Not Track" signals because we do not track you.

### 8.7 Other countries

If the law of your country gives you additional rights over your personal data, we will honor them to the extent they apply to us. Write to the address in section 14.

## 9. Children

The App is not directed to children, and we do not knowingly collect personal information from children under 13. Do not use the App or upload photos of children under 13. Where the law of your country sets a higher minimum age for consenting to the processing of personal data (for example 14 in South Korea, and 14 to 16 in several European countries), you must be at least that age, or have the consent of a parent or guardian, to use the App. If you believe a child's information was sent to us, contact {{SUPPORT_EMAIL}} and we will delete it.

## 10. Automated processing and biometrics

Portraits are created by an AI model from your photo and a look chosen by us. We make no decisions about you that have legal or similarly significant effects, and we do not profile you. The only automated checks are fraud and abuse controls (for example limits per device and content safety filters); if a creation is declined, you can try again with another photo or contact us.

We do not use biometric identification. Face detection runs on your device only to check that a face is present and to count faces. We do not create or store face templates, we do not compare faces, and we do not use faces to identify anyone. The face rectangle (position and size only) that stays on your phone for the before/after comparison is not a face template, is used for nothing else, and is never sent to us.

## 11. Photos of other people

Only add photos of people who agreed to this. Photos of other people are sent to the AI service just like your own. You are responsible for having their permission.

## 12. Security

Data moves between the App, our backend, and the AI service over encrypted connections (HTTPS/TLS). Our cloud providers encrypt stored data at rest. The OpenAI API key is kept on our server and is never inside the App. No system is perfectly secure, so we cannot guarantee absolute security. If a breach affects your personal data, we will notify you and the authorities as the law requires.

## 13. Changes, and this website

If we change this policy in a meaningful way, we will update the date above and, if the change affects what is sent to the AI service, ask for your permission again in the App. If this policy is shown in your language, the translation is provided for convenience; the English version prevails if the versions differ.

This website is static. It sets no cookies and uses no analytics or external resources. It is hosted on GitHub Pages, and GitHub may process technical data such as your IP address when your browser loads a page.

## 14. Contact

{{DEVELOPER_NAME}}
{{SUPPORT_EMAIL}}
{{SITE_URL}}/privacy.html

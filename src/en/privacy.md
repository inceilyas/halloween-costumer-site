title: Privacy Policy
description: How {{APP_NAME}} handles your photos and data: what is sent to the AI service, legal bases, what is stored and for how long, and your rights worldwide.

# Privacy Policy

> Effective date: {{EFFECTIVE_DATE}}

{{APP_NAME}} (the "App") turns your photos into Halloween monster portraits using a third-party AI image service. This policy explains what information the App handles, why and on what legal basis, who receives it, how long it is kept, and what rights and choices you have, wherever you live. The App is operated by {{DEVELOPER_NAME}} ("we", "us"), the controller of your personal data (the party that decides how and why it is processed). Our contact details are in section 14.

## 1. The short version

- Photos you choose are sent to an outside AI service (OpenAI) only to create the portrait you asked for. We ask for your clear permission before the first time this happens, and you can withdraw it at any time.
- We do not keep the photos you send. We forward them, in memory, to the AI service and send the result back to your phone.
- Your finished portraits are saved on your phone. So that a portrait is not lost if your connection drops or the App is closed while it is being made, we keep a copy of each newly generated portrait, encrypted, on our server for at most 24 hours. It is used only to deliver the portrait to your phone, and it is deleted as soon as your phone confirms it was saved, or after 24 hours at the latest.
- We do not use your photos or your face to train AI models, for advertising, or for analytics. We do not identify or recognize people from their faces.
- There is no account, no advertising or analytics SDK, and no tracking across other companies' apps and websites.
- You can delete your data from inside the App at any time (Profile > Delete all my data) and withdraw your AI consent (Profile > Withdraw AI consent).

## 2. Information we handle

**a. Photos you choose or take.** When you pick a photo from your library or take one with the camera, and tap to create a portrait, the photo (a resized JPEG) and the look you selected are sent to our backend and on to the AI service. If you choose a group or couple look with separate selfies, each selfie is sent. Photos can show the faces of you and of other people. We only access photos you explicitly choose; the App does not scan your photo library.

**b. Face check on your device.** Before a photo is sent, the App uses Apple's Vision framework on your device to check that a suitable number of faces is present (for example, exactly two for a couple look). This check runs entirely on your phone. It finds where faces are and how many there are. It does not create a face template or any biometric identifier, it does not identify or recognize who anyone is, and its results are not stored or sent anywhere except as a face count used to write the instructions for the AI service.

**c. Generated portraits.** The AI service's result comes back to the App and is saved on your phone. A temporary copy of each generated portrait is kept encrypted in our cloud storage for at most 24 hours, only to deliver it to your phone if the connection fails; your selfies and other input photos are never stored.

**d. Anonymous identifier and credits.** The App creates an anonymous Firebase identifier for your installation. We use it to keep your credit balance and to record purchases and credit movements (transaction ID, product, date). We do not ask you to create an account and we do not collect your name, email address, or phone number in the App. When we call the AI service we include a pseudonymous identifier derived from your anonymous ID with a one-way keyed hash; it is not your real identifier and the AI service cannot link it to you. It helps the AI service detect abuse.

**e. Purchases.** Purchases and subscriptions are processed by Apple. We never receive your payment card or Apple Account details. We receive confirmation of a transaction (transaction ID, product, dates, renewal or refund status) so we can grant or remove credits. If you tap Restore Purchases, the App sends the purchase records that Apple has signed to our server so we can verify them and re-link your purchases and remaining credits to the App on this device. These records contain the product, dates and the random per-install purchase identifier we generated; they do not contain your name, email address or payment details. If the records match another install of the App, the remaining credits of that install are moved (not copied) to this one. Restore needs no sign-in and creates no new kind of personal data.

**f. Device integrity.** To protect the service from abuse, we use Apple's App Attest (through Firebase App Check) to confirm requests come from a genuine copy of the App, and Apple's DeviceCheck to remember, with a single on/off setting stored by Apple, that a device has already used its free first portrait. DeviceCheck does not tell us who you are.

**g. Technical logs.** Our cloud services and the AI service may log technical information such as IP address, request time, and error codes for security and to operate the service. Our own code does not write photos, face data or personal data into logs. We do not use these logs to build profiles about you.

**h. Messages to support.** If you email us, we receive your email address and what you write, and we use it only to reply.

**i. On-device settings.** The App stores simple preferences on your phone (for example, that you finished onboarding and that you agreed to the AI notice).

We do not collect your precise location, contacts, health data, or browsing history.

## 3. Why we use it, and legal bases

| Purpose | Information | Legal basis (GDPR and UK GDPR; equivalent bases under other laws) |
| --- | --- | --- |
| Create the portrait you ask for: send your photos and the chosen look to the AI service | Photos, selected look, face count, pseudonymous identifier | Your consent (Art. 6(1)(a)), given in the App before the first creation. You can withdraw it at any time; withdrawing does not affect earlier processing. |
| Credits, purchases, subscriptions, Restore Purchases, refunds of credits | Anonymous identifier, credit balance, purchase records | Performance of our contract with you (Art. 6(1)(b)); keeping records we must keep by law (Art. 6(1)(c)) |
| Prevent fraud and abuse, enforce the one free portrait per device, keep the service secure (App Check, DeviceCheck, rate limits, safety filters, logs) | Anonymous identifier, device integrity signals, technical logs | Our legitimate interests in protecting the service, other users and ourselves (Art. 6(1)(f)). You may object (section 7). |
| Answer support requests | Email address, message, Support ID | Our contract with you and our legitimate interest in helping you |
| Comply with law and handle legal claims | Records described in section 6 | Legal obligation and legitimate interests |

**Faces and photos.** Faces and photos in your pictures are used only to generate the portrait you requested. They are not used to train or improve any AI model, for advertising or marketing, for analytics or profiling, or sold or shared for those purposes. We do not build a database of faces, and we do not analyze photos to infer sensitive characteristics about anyone.

If you do not agree to send photos to the AI service, you can still open the App, but it cannot create portraits.

## 4. Who receives information

We share information only with the service providers needed to run the App:

- **OpenAI** (image generation). Your photos and the selected look are sent to OpenAI's API to produce your portrait. OpenAI acts as our processor. According to OpenAI's published API data policy, data sent to the API is not used to train or improve OpenAI's models unless the customer opts in (we have not opted in), and API content may be kept in abuse-monitoring logs for up to 30 days, or longer if required by law or needed to protect services. OpenAI's policy: https://developers.openai.com/api/docs/guides/your-data . OpenAI may also screen uploaded images for child sexual abuse material and keep a flagged image for review as described in that policy.
- **Google (Firebase and Google Cloud)** (backend hosting, anonymous identifier, credit and purchase records, app integrity checks, temporary encrypted storage of generated portraits). Google acts as our processor under its data processing terms. Our backend runs in the United States (Iowa).
- **Apple** (App Store purchases, App Attest, DeviceCheck, and optional sharing of your portraits via the iOS share sheet that you start yourself). Apple acts as an independent controller for its own services.
- **Authorities or successors**, when required by law or to protect rights and safety, or as part of a business transfer, with notice where required.

We do not sell your personal information, and we do not share it for cross-context behavioral advertising.

When you share a portrait to another app (for example from the share sheet), that app's own privacy policy applies to what you share.

## 5. International transfers

We are based in Türkiye, and our providers process data in the United States and possibly other countries where they operate. If you use the App in the European Economic Area, the United Kingdom, Switzerland, Türkiye, Brazil, South Korea, Japan or elsewhere, your information is therefore transferred to other countries, including countries whose data protection law may differ from yours.

We use the safeguards that your law requires for such transfers, where they apply: an adequacy decision (for example the EU-US Data Privacy Framework, where the recipient participates), standard contractual clauses (EU and the UK addendum) in our providers' data processing terms, other lawful mechanisms recognized by local law (see section 8), and your consent where the law allows it. We also limit what is sent to what is needed, use encrypted connections, and do not send your name, email address or real account identifier to the AI service. You can ask us for information about the safeguards (section 14).

## 6. How long we keep information

| Information | Retention |
| --- | --- |
| Photos sent for a creation | Not stored by us. Held in memory only while the request is processed. The AI service may keep them for up to 30 days in abuse-monitoring logs (see section 4). |
| Generated portraits | On your phone until you delete them or use Delete all my data. A temporary delivery copy is kept encrypted on our server for at most 24 hours (deleted when your phone confirms the save, and by Delete all my data). |
| Anonymous identifier, credit balance, credit movements, purchase records (including those used by Restore Purchases) | Until you delete your data in the App. Records with a zero balance and no activity for 24 months are deleted. |
| Purchase transaction records after you delete your data | Transaction ID, product and dates are kept without any link to your anonymous identifier, to process refunds and avoid granting credits twice, and where law requires (for example for accounting). |
| Deletion marker | After you delete your data we keep your former random anonymous identifier and the deletion time, so that the deleted record cannot be re-created. It contains no other information. |
| Technical logs | A limited period needed for security and operations (for example, Firebase Authentication logs IP addresses for a few weeks). |
| Support emails | As long as needed to help you, then deleted. |

## 7. Your rights and choices

Depending on where you live, you have some or all of these rights: to know whether we process your data and to get a copy (access); to correct it; to delete it; to restrict processing; to receive your data in a portable format; to object to processing based on legitimate interests; to withdraw consent at any time; not to be subject to decisions based solely on automated processing with legal or similarly significant effects (we make none); and to complain to a data protection authority.

How to use them:

- **Delete all my data (in the App).** Profile > Delete all my data removes the portraits, selfie thumbnails, and AI consent stored on your phone and asks us to delete the server-side record linked to your anonymous identifier (credit balance and purchase records). Unused credits are forfeited when you do this. Deleting the App alone does not delete the server-side record.
- **Withdraw AI consent.** Profile > Withdraw AI consent. Photos will not be sent again until you agree again.
- **Access, portability, correction, restriction, objection.** Email {{SUPPORT_EMAIL}} and include the Support ID shown in the Profile tab, so we can find your record. We cannot look up your data without it, because the App is anonymous. We will send you the record linked to your Support ID (credit balance, credit movements and purchase records) in a common, machine-readable format. Your portraits are already on your phone.
- **Photo access.** You can change camera and photo permissions in iOS Settings. The App uses the system photo picker, which gives it access only to photos you select, and saves to your library only when you tap Save.
- **Subscriptions** are managed or cancelled in your Apple Account settings (see our Terms of Use).

We answer within one month (GDPR and UK GDPR; we may extend by up to two further months for complex requests and will tell you), or within the period set by the law that applies to you. We may ask you to confirm that a request comes from the owner of the Support ID. You can also complain to your local data protection authority (in the EEA, the authority of the country where you live or work; in the UK, the Information Commissioner's Office; in Türkiye, the Personal Data Protection Authority; in Brazil, the ANPD; in South Korea, the PIPC; in Japan, the PPC). We would appreciate the chance to resolve your concern first.

## 8. Information for specific regions

### 8.1 European Economic Area, United Kingdom and Switzerland

{{DEVELOPER_NAME}} is the controller. The legal bases are in section 3, transfers in section 5, retention in section 6, and your rights in section 7, including the rights to object and to withdraw consent. We have not appointed a data protection officer; privacy questions go to the address in section 14. Where the law of your country sets a higher age for consenting to the processing of personal data than 13 (for example 14 to 16 in several European countries), see section 9.

### 8.2 Türkiye (Law No. 6698, KVKK)

{{DEVELOPER_NAME}} is the data controller. We process personal data for the purposes in section 3, on the grounds of your explicit consent (sending photos to the AI service), the establishment and performance of a contract, our legitimate interests (fraud prevention and security), and legal obligations. Under Article 11 of Law No. 6698 you may ask whether your data is processed, request information, learn the purpose and whether it is used appropriately, know the third parties to whom it is transferred in Türkiye or abroad, ask for correction or deletion, ask that these actions be notified to third parties, object to results against you, and claim compensation for damage. Apply to us at the address in section 14, with your Support ID; we answer within thirty days at the latest. If you are not satisfied, you may complain to the Personal Data Protection Board (KVKK). Data is transferred abroad (section 5) under the conditions of Article 9 of Law No. 6698.

### 8.3 Brazil (LGPD)

{{DEVELOPER_NAME}} is the controller and the contact for data subjects is the address in section 14. Our legal bases under Article 7 of Law No. 13.709/2018 are consent, performance of a contract, regular exercise of rights, and legitimate interests. You have the rights in Article 18 (confirmation of processing, access, correction, anonymization, blocking or deletion, portability, information about sharing, information about the consequences of refusing consent, and revocation of consent) and may petition the ANPD. International transfers are made as set out in section 5 and Article 33 of the LGPD.

### 8.4 South Korea (PIPA)

We process the personal information in section 2 only for the purposes in section 3 and keep it for the periods in section 6. We do not provide personal information to third parties other than as described in section 4. We entrust the processing described in section 4 to OpenAI and Google, and we oversee them through contract terms. Your photos and related information are transferred overseas as follows, with your consent given in the App:

| Recipient and country | Items | Purpose | When and how | Retention |
| --- | --- | --- | --- | --- |
| OpenAI, United States | Photos, selected look, pseudonymous identifier | Generate the portrait | Each time you create a portrait, over an encrypted network | Up to 30 days in abuse-monitoring logs |
| Google (Firebase and Google Cloud), United States | Anonymous identifier, credit and purchase records, temporary copy of the generated portrait | Hosting, credit ledger, delivery of the portrait | Each time you use the App, over an encrypted network | As in section 6 |

You may exercise your rights to access, correct, delete, suspend processing, and withdraw consent under PIPA by contacting us at the address in section 14; you may refuse consent, but then the App cannot create portraits. The person responsible for privacy is {{DEVELOPER_NAME}} ({{SUPPORT_EMAIL}}). You can also seek help from the Personal Information Protection Commission or the KISA Privacy Center (118).

### 8.5 Japan (APPI)

{{DEVELOPER_NAME}} is the business operator handling personal information. We use personal information only for the purposes in section 3. When you consent in the App, your photos and related information are provided to businesses in a foreign country: OpenAI and Google, in the United States and other countries where they operate. The United States has no single comprehensive personal information protection law like the APPI; our providers handle the data under their own commitments and contract terms described in section 4 (no training on API data, limited retention, encryption). You may request disclosure, correction, deletion and cessation of use of retained personal data, and a record of third-party provisions, by contacting us at the address in section 14.

### 8.6 United States

Depending on where you live (for example California, Colorado, Connecticut, Virginia, Texas, Oregon, and other states with consumer privacy laws), you may have the right to know what personal information we hold, access it, correct it, delete it, receive a portable copy, and appeal our decision. We do not sell personal information, do not share it for targeted advertising, and do not use it for profiling that has legal or similarly significant effects. We do not process photos to uniquely identify a person. To use these rights, use Delete all my data in the App or email {{SUPPORT_EMAIL}}; we will respond within 45 days (we may extend once where the law allows) and will not discriminate against you for exercising your rights. You may use an authorized agent; we may ask for the Support ID to verify the request. If we deny a request you may appeal by replying to our email, and you may contact your state attorney general.

California "Shine the Light" and Nevada requests can be sent to the same address. We do not respond to "Do Not Track" signals because we do not track you.

### 8.7 Other countries

If the law of your country gives you additional rights over your personal data, we will honor them to the extent they apply to us. Write to the address in section 14.

## 9. Children

The App is not directed to children, and we do not knowingly collect personal information from children under 13. Do not use the App or upload photos of children under 13. Where the law of your country sets a higher minimum age for consenting to the processing of personal data (for example 14 in South Korea, and 14 to 16 in several European countries), you must be at least that age, or have the consent of a parent or guardian, to use the App. If you believe a child's information was sent to us, contact {{SUPPORT_EMAIL}} and we will delete it.

## 10. Automated processing and biometrics

Portraits are created by an AI model from your photo and a look chosen by us. We make no decisions about you that have legal or similarly significant effects, and we do not profile you. The only automated checks are fraud and abuse controls (for example limits per device and content safety filters); if a creation is declined, you can try again with another photo or contact us.

We do not use biometric identification. Face detection runs on your device only to check that a face is present and to count faces. We do not create or store face templates, we do not compare faces, and we do not use faces to identify anyone.

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

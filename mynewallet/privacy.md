# Privacy Policy — MyneWallet | The Brink Labs

> MyneWallet collects no personal data. No account, no servers, no analytics. Your financial records stay in an encrypted database on your own device.

Canonical: https://thebrinklabs.com/mynewallet/privacy.html  
Source: The Brink Labs · support@thebrinklabs.com · Last reviewed 2026-09-07

---

The Brink Labs · MyneWallet

## Privacy Policy.

Most privacy policies are written to explain what a company does with your data. This one is short because there is nothing to explain. MyneWallet has no user accounts, no servers and no analytics. Your financial records are written to your own device and they stay there.
The One-Minute Version

## Eight Questions. Eight Answers.

Contents
- Who we are
- The data we collect
- Local-first architecture
- Network & Google APIs
- Device permissions
- Security
- Children’s privacy
- Your rights
- Retention & deletion
- International transfers
- Third parties
- Liability
- Changes
- Contact

## Who we are

The Brink Labs (“we”, “us”, “our”) develops and publishes the MyneWallet mobile application (the “App”). This policy describes how information is handled when you use the App. It is written to be read, not to be survived. If any part of it is unclear, write to us and we will fix the wording — see Section 14.

## The data we collect: none

We do not collect personal data through the App. Specifically, we do not collect, receive, transmit, log, profile or monetise any of the following:
- Transactions, amounts, categories, tags, payees, notes or account names
- Balances, budgets, envelopes, goals, obligations, loans or net worth
- Names, email addresses, phone numbers or contacts
- Bank credentials, card numbers or financial institution identifiers
- Precise or coarse location, advertising identifiers or device fingerprints
- Usage analytics, screen views, session lengths, feature telemetry or crash traces
There is no sign-up screen in MyneWallet because there is no account to sign up for. The App is fully functional on a device that has never been connected to a network.

## Local-first architecture

MyneWallet is engineered as an offline-first application. This is an architectural property, not a setting you have to find.
- On-device storage. All financial records, budgets, settings and preferences are written to an encrypted SQLite database held inside your device’s private application sandbox, which the operating system isolates from other apps.
- No remote database. We do not own, rent or operate any server, database or storage bucket that holds your financial data. There is no copy of your ledger for us to lose, leak, subpoena or sell.
- No third-party data pipelines. The App contains no advertising network, no attribution SDK and no product-analytics SDK. Google’s Firebase suite is not integrated into the App.
- No background transmission. The App does not upload your data on a schedule, on launch, or on any trigger you did not initiate yourself.

## When the App uses the network, and Google API Limited Use

MyneWallet makes network requests in only two situations, both initiated by you.

### 4.1 Optional encrypted backup to your own Google Drive

To protect you against a lost or replaced phone, the App offers an opt-in backup of your local database to your Google Drive account.
- You turn it on. Backup is off until you enable it and complete Google OAuth consent yourself. Nothing is uploaded before that.
- Encrypted before it leaves. The backup file is encrypted on your device using AES-256 with a randomised initialisation vector, then transferred over TLS. The file that reaches Drive is ciphertext.
- It is your Drive, not ours. The file lands in your own Google account. We have no access to your Drive, your Google credentials, your OAuth tokens or your encryption keys, and we receive no copy or notification of your backups.
- You can revoke it at any time from your Google Account permissions page, and delete the backup file from Drive yourself.
Google API Services User Data Policy. MyneWallet’s use and transfer of information received from Google APIs to any other app will adhere to the Google API Services User Data Policy, including the Limited Use requirements. We request the narrowest Drive scope that allows the App to write and read back its own backup file, and we use that access for no purpose other than the backup and restore feature you asked for. We do not use Google user data for advertising, we do not transfer it to third parties, and we do not allow humans to read it.

### 4.2 Purchases through Google Play Billing

The optional PRO unlock is processed entirely by Google Play Billing. Payment happens inside Google’s own flow — we never see, handle or store your card number, billing address or Google account identity. The App receives only a signed purchase receipt confirming entitlement. Google’s handling of that transaction is governed by Google’s Privacy Policy.

## Device permissions

Every permission the App requests exists to deliver a feature you can see, and none of them is used to gather information about you:
- Network access — used only for the two purposes in Section 4. With backup disabled and no purchase in progress, the App has no reason to reach the network.
- Biometrics and device credential — used only to satisfy the App Lock you enable. Biometric data never leaves the secure hardware of your device and is never seen by the App or by us.
- Notifications — used only for local reminders and summaries generated on your device. There is no push server; we cannot send you a message.
- File access — used only when you personally choose a file to import, or a destination to export a CSV or PDF statement to.

## Security

- Your ledger is stored inside the OS-enforced private app sandbox.
- Backups are encrypted with AES-256 and a randomised initialisation vector before transfer.
- App Lock can require biometrics, a PIN or a pattern before the App will open.
- Block Screenshots prevents screenshots, screen recording and app-switcher previews of your balances.
- A one-tap privacy mask hides every monetary figure on screen.
No system is perfect, and we will not pretend otherwise. What we can say precisely is that a breach of our infrastructure cannot expose your financial data, because your financial data is not on our infrastructure.
Responsible disclosure. Found a security issue? Email support@thebrinklabs.com with “Security” in the subject line. We will acknowledge you, and we will not take legal action against good-faith research.

## Children’s privacy

MyneWallet is not directed to children. The App is intended for users aged 13 and over, or 16 and over where local law (including the GDPR as implemented in your country) sets a higher age of digital consent. We do not knowingly collect personal information from children — a claim that is simple for us to honour, since we do not knowingly collect personal information from anyone.

## Your rights, and why they are already satisfied

Privacy law in your region — the GDPR, the UK GDPR, the CCPA/CPRA and comparable regimes — gives you rights of access, correction, portability, erasure and objection over personal data a company holds about you.
We hold no personal data about you, so there is nothing for us to disclose, correct or delete on your behalf, and no profile to object to. In practice your rights are exercised directly and instantly inside the App:
- Access and portability — export your full ledger to CSV, or generate a PDF statement, at any time.
- Correction — edit or delete any record yourself.
- Erasure — clear the App’s storage or uninstall it. If you enabled Drive backup, delete the backup file from your own Drive and revoke the App’s access from your Google Account permissions page.
We do not sell or share personal information as those terms are defined under the CCPA/CPRA, and we have never done so.

## Data retention and deletion

Because your data lives on your device, you control its entire lifecycle. We retain nothing, so we have no retention period to publish. Uninstalling the App, or clearing its storage from your device settings, removes the local database permanently. This cannot be undone by us — keep a backup before you do it.

## International data transfers

None occur through the App. Your data does not cross a border because it does not leave your device. If you enable Google Drive backup, the storage location of your own Google account is determined by Google under your agreement with Google, not by us.

## Third parties

We have no data-sharing relationships. The only third parties involved in the App at all are Google Play (distribution and billing) and, if you switch it on, Google Drive (storage of your own encrypted backup, in your own account). Neither receives your financial records from us, because we never have them.

## Accuracy and limitation of liability

MyneWallet is provided on an “as is” and “as available” basis. It is a personal record-keeping and planning tool, not financial, tax, investment or legal advice, and it does not connect to your financial institutions to verify anything. You are responsible for the accuracy of what you enter, for the decisions you make, and for maintaining your own backups. To the fullest extent permitted by law, The Brink Labs is not liable for data loss arising from device failure, device loss, uninstallation, storage clearing, operating-system changes, or a decision not to use the optional backup feature.

## Changes to this policy

If this policy changes, we will update the effective date at the top of this page. If a future version ever introduces a genuine collection of personal data — which is not our intention — we will say so plainly at the top of this page and inside the App before it takes effect, rather than burying it in a diff.

## Contact

Questions about this policy, your data, or anything else: support@thebrinklabs.com. Data controller: The Brink Labs. We aim to answer within five business days.
Back to MyneWallet

---

This is the markdown representation of https://thebrinklabs.com/mynewallet/privacy.html, published so that AI agents and answer engines can read the page without parsing HTML. The full index of machine-readable resources is at https://thebrinklabs.com/llms.txt

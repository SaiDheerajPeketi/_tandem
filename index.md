# Privacy Policy for Tandem

**Effective date:** September 27, 2026  
**Developer:** Black and Blue

Tandem is an Android care-tracking app for parents and other caregivers. It records feeding, sleep, diaper, pumping, growth, milestones, and notes. This policy explains what Tandem processes, why it is used, and the choices available to you.

Tandem does not sell personal data, show third-party advertising, or make care records public.

## 1. Information stored on your device {#privacy}

Tandem can store a baby's name and approximate birth date, caregiver name and role, care events, growth measurements, milestones, notes, edit history, and app preferences in app-private Android storage protected with an Android Keystore-backed key. Android backup and device transfer are disabled for Tandem data. If you use optional Family Pro, the care-log categories described in section 5 can also be synchronized to the family service; the baby's local profile metadata is not synchronized.

You control what you enter. Avoid adding information that is not needed for caregiving.

## 2. Local export and sharing

Tandem can create a CSV export of care-log entries for a selected local baby profile. The app opens Android's share chooser, and you decide whether to send the file and which installed app receives it. Tandem does not automatically upload exports. A receiving app's privacy practices apply after you share the file.

## 3. Analytics and crash diagnostics

Tandem uses Google Analytics for Firebase to record that the Android app was opened and Firebase Crashlytics to receive crash reports and developer-recorded non-fatal diagnostics. These services may process app-instance identifiers, app version, device model, operating-system information, coarse location inferred from network information, app-interaction events, crash logs, diagnostics, and network information such as IP address.

Tandem does not attach baby profiles, caregiver names, care records, notes, exports, purchase identifiers, or advertising identifiers to analytics or crash events. Advertising-ID collection and ad-personalization signals are disabled, and the Android release removes advertising and AdServices identifier permissions.

## 4. Optional purchases

Tandem may offer optional, repeatable **Student Developer Support** purchases at locally displayed store prices corresponding to US $1, $10, and $100 tiers. These purchases support the developer; they do not unlock paid features, create a lasting entitlement, make a charitable donation, or provide a tax deduction.

Google Play processes payment. RevenueCat helps validate purchases and may process purchase history, product and transaction identifiers, an app-user identifier, app/device/operating-system information, and network information such as IP address. Tandem does not receive full payment-card details and does not send care records to Google Play or RevenueCat.

For each eligible transaction made after Tandem's local baseline, the app may add one local Support Spark for an optional thank-you celebration. Tandem stores one-way fingerprints instead of raw provider customer or transaction identifiers. Clearing or deleting local data removes the Spark ledger; past purchases are not restored as owned content.

## 5. Optional Family Pro service

Where Family Pro is available in your installed version, you can create a cloud account using an email address and password, then create or join one caregiver family. Supabase Auth processes your email address, account identifier, authentication tokens, and sign-in information. Family setup processes the family name, your chosen display name and role, membership, and invitations. Invitation codes expire after seven days; the service stores a one-way hash of each code rather than the code itself.

An active Family Pro subscription allows authorized family members to synchronize feeding, sleep, diaper, and pumping logs, including notes entered on those logs. These shared logs, their edits, and deletion history are stored in the family's Supabase project in India's Mumbai region (`ap-south-1`). Other active family members can view and edit the shared logs. Baby profile metadata, growth measurements, milestones, and notes outside those four log types are not part of this cloud sync. Access to sync and invitations closes when Family Pro is not verified, but previously stored family data is not automatically deleted at subscription expiry.

To validate Family Pro, the server receives purchase-event identifiers, product and subscription state, and the app-user identifier from RevenueCat. It links that state to your cloud account so it can authorize family access. Payment-card details and care-log contents are not sent to RevenueCat. Cloud log changes keep version history, including deleted-log tombstones, until the owner deletes the family or their cloud account. These records are not public and are accessible only to currently authorized family members and service administrators who need access to operate or protect the service.

## 6. Service providers

Tandem uses:

- **Google Firebase** for analytics and crash diagnostics.
- **Google Play** for app distribution and payment processing.
- **RevenueCat** for purchase validation.
- **Supabase** for optional cloud authentication, family membership, and Family Pro synchronization.

These providers process data under their own terms and may process it in countries other than yours. Service traffic uses encrypted HTTPS connections.

## 7. Retention and security

Local records remain until you delete Tandem's local profile and data, clear the app's storage, or uninstall the app. Optional cloud family data, including log versions, remains until the family owner deletes the family or their cloud account. A caregiver who leaves or deletes their own account loses access, but the owner's family records remain. Deleting the owner account removes its family and shared logs. Uninstalling the app or deleting only local data does not delete a cloud account or family data. Google Play, RevenueCat, Firebase, and Supabase may retain provider records under their settings, legal obligations, fraud-prevention needs, and applicable policies. The family service may retain purchase-event receipts without a link to a deleted account for replay prevention.

Tandem uses Android app-private storage, Android Keystore-backed encryption, disabled Android backup and transfer, and encrypted network connections. No storage or transmission method is completely risk-free. Protect access to your device and keep Android security updates current.

## 8. Delete Tandem data {#delete-tandem-data}

In Tandem, open **Settings & Account → Privacy & Local Data → Delete Local Profile & Data**, review the warning, and confirm deletion. This removes the local profile and child records, Support Spark ledger, pending and celebration state, cached CSV exports created by Tandem, and Tandem's local encryption-key alias.

You can also clear Tandem's storage in Android settings or uninstall the app. These actions do not delete provider purchase, analytics, or crash records. Copies you already shared with another app are outside Tandem's control.

If you created a Family Pro cloud account, open **Settings & Account → Family account → Delete cloud account** while signed in, review the warning, and confirm. This permanently removes your cloud account; if you own a family, its shared logs and memberships are also deleted. If you are a caregiver in someone else's family, deleting your account removes your membership but not the owner's family records. You may separately delete local data using the steps above. If you cannot sign in, use the contact address below to request help with cloud account or family-data deletion; we may ask for the minimum information needed to verify ownership.

For help identifying or deleting provider information that Black and Blue can administer, email **developer@blackandblue.co.in** with the subject **Tandem privacy request**. Include only the minimum locator requested by support. Do not send baby or caregiver records, passwords, payment-card information, authentication links, or raw purchase tokens.

## 9. Children

Tandem contains information about babies and children, but it is designed for parents and other caregivers to operate, not for children to use independently. It does not contain advertising, public profiles, or social features. A caregiver controls any export through Android's share chooser. A parent or guardian may contact us if they believe information was provided through inappropriate use of the app.

## 10. Terms of use {#terms}

Use Tandem only for lawful caregiving and with appropriate authority to record the information entered. Tandem is a record-keeping aid, not medical, emergency, diagnostic, or professional advice. Contact a qualified professional or emergency service when appropriate.

Tandem is provided on an “as available” basis. Purchase prices and terms are shown by Google Play before purchase and are subject to Google Play's billing and refund rules.

## 11. Support {#support}

For product help, billing questions, privacy requests, or safety concerns, email **developer@blackandblue.co.in**. Include the app name, app version, Android version, device model, and a concise description when relevant, but do not send private care records or secrets.

## 12. Changes

We may update this policy when Tandem, its providers, or legal requirements change. The current version will show its effective date. Material changes will be reflected in the app or store listing when appropriate.

## 13. Contact

- **Developer:** Black and Blue
- **Email:** developer@blackandblue.co.in
- **Privacy page:** https://tandem.blackandblue.co.in/

Users in India may send privacy questions or complaints to the email address above. This contact statement does not designate a statutory grievance officer or publish unverified legal or postal details.

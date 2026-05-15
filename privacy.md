# Sundri — Privacy Policy

**Last updated: 15 May 2026**

Sundri ("we", "us", "the app") is a Punjabi suit discovery and inspiration app developed by Harman ("the developer"), based in Queenstown, New Zealand. This Privacy Policy explains what information we collect, why we collect it, and how it's stored.

---

## 1. Information We Collect

### Information you give us
- **Phone number.** Required to create an account and sign in. Used solely for authentication via one-time SMS codes.
- **Display name (optional).** Shown only to you within the app.

### Information collected automatically
- **Saved looks.** When you tap the heart icon on a suit, we record the suit ID and timestamp linked to your account so your shortlist syncs across devices.
- **Anonymous usage events.** When you view, swipe, save, or share a suit, we log the event (without any personally identifying information beyond your user ID). Used only to improve which suits we surface.
- **Device push token (optional).** If you enable notifications, we store the token issued by Apple/Google so we can deliver notifications.

### What we don't collect
- We do not collect your name (unless you choose to enter one), email address, photos, contacts, location, or biometric data.
- We do not access your camera, microphone, photo library, or contacts.
- We do not track you across other apps or websites.
- We do not sell your data. Ever.

---

## 2. How We Use Your Information

| Information | Purpose |
|---|---|
| Phone number | Sign-in via SMS one-time code; preventing duplicate accounts |
| Display name | Personalising the greeting in the app |
| Saved suits | Showing your shortlist on every device you sign in on |
| Usage events | Improving which suits we generate and surface |
| Push token | Sending the optional daily notification |

We do not use your information for advertising, profiling, or any purpose beyond running the app.

---

## 3. How We Store and Protect Your Information

- **Database:** Supabase (PostgreSQL), hosted in Mumbai, India.
- **Images:** Cloudflare R2 (object storage).
- **SMS delivery:** Twilio.
- **Push delivery:** Apple Push Notification service / Firebase Cloud Messaging via Expo Push Service.

All connections use HTTPS/TLS. Database access is restricted by Row-Level Security policies so users can only access their own data.

We retain your data only as long as your account is active. If you delete your account or request deletion, all your data is permanently erased within 30 days.

---

## 4. Sharing With Third Parties

We share information only with the service providers strictly required to operate the app:

- **Supabase Inc.** (database hosting) — stores your account row, saved suits, profile.
- **Cloudflare Inc.** (image delivery) — serves images to your device. Does not receive your account information.
- **Twilio Inc.** (SMS delivery) — receives your phone number to deliver the one-time code.
- **Apple Inc. / Google LLC / Expo** (push notification delivery) — receives your device token and notification content.

We do not share your data with advertisers, brokers, analytics platforms, or any other parties.

---

## 5. Your Rights

You can, at any time:

- **View and edit your name** from the Account screen
- **Turn off notifications** from the Account screen
- **Sign out** to immediately stop collection
- **Request account deletion** by emailing us (see Contact below). Your account, saved suits, and all associated data are deleted within 30 days
- **Request a copy of your data** by emailing us

If you are a resident of the European Union, United Kingdom, or California, you may have additional rights under GDPR / UK GDPR / CCPA, including the right to access, rectify, restrict, or object to processing of your data. Contact us to exercise any of these rights.

---

## 6. Children

Sundri is not directed at children under 13. We do not knowingly collect information from children under 13. If you believe a child has provided us information, contact us and we will delete it.

---

## 7. Security

We protect your information using industry-standard practices:
- HTTPS/TLS for all network requests
- Row-Level Security on database tables
- Authentication tokens stored in secure device storage (iOS Keychain / Android Keystore)
- Phone OTP codes expire after 60 seconds
- No passwords stored — sign-in is via one-time SMS code only

No system is perfectly secure, but we take reasonable care.

---

## 8. Changes to This Policy

We may update this Privacy Policy occasionally. If we make a material change, we will notify you in-app before the change takes effect. The "Last updated" date at the top reflects the most recent revision.

---

## 9. Contact

For privacy questions, data access, or deletion requests, contact:

**Harman**
Sundri App
Email: heyrajbrar@gmail.com
Based in: Queenstown, New Zealand

---
layout: legal
title: "Privacy Policy"
lang: en
direction: ltr
description: "How Unfolio handles your data: everything is processed on your device, nothing is uploaded."
permalink: /privacy-policy-en/
---

# Unfolio — Privacy Policy

**Effective date:** 3 August 2026
**Last updated:** 3 August 2026

**Publisher:** Afek Hasson, an individual developer based in Israel
**Contact:** afekhasson7@gmail.com

*Other versions: [מדיניות פרטיות (עברית)](privacy-policy-he.md) · [Terms of Service](terms-en.md)*

---

## The short version

Unfolio has no server, no account, and no login. You never give us — or the app — your Instagram password, because the app has no way to use one.

Your Instagram data export is opened and analysed **on your phone**. The follower and following lists it produces stay on your phone. They are never uploaded, never sent to us, and never shared with anyone. We could not read them even if we wanted to; there is nowhere for them to go.

The only information that ever leaves your device is what is needed to confirm that your subscription is valid — handled by Apple, Google and RevenueCat, and described in Section 7.

We do not use analytics. We do not use advertising. We do not track you.

The rest of this policy says the same thing in more detail, and tells you what your rights are.

---

## 1. Who we are

Unfolio ("Unfolio", "the app") is published by **Afek Hasson**, an individual developer based in Israel.

For the purposes of the EU General Data Protection Regulation (GDPR), the UK GDPR, and Israel's Privacy Protection Law, 5741-1981, Afek Hasson is the **data controller** for the limited personal data described in this policy.

You can reach us at any time at **afekhasson7@gmail.com**. We answer in Hebrew or English.

This policy explains what happens to information when you use Unfolio. It applies to the Unfolio mobile app on iOS and Android.

## 2. What Unfolio does

Instagram does not tell you who has stopped following you. Instagram does, however, let you download a copy of your own information — a feature it calls "Download Your Information" or "Export Your Information."

Unfolio helps you use that file:

1. You request your own data export from Instagram. You do this yourself, inside Instagram, using your own account. Unfolio is not involved in this step and cannot do it for you.
2. Instagram sends the export to you as a ZIP file.
3. You open that ZIP file in Unfolio.
4. Unfolio reads the file **on your device**, compares your followers list against your following list, and shows you the result: who does not follow you back, who you do not follow back, and who follows you mutually.

That is the whole product. There is no step in which anything is uploaded.

## 3. What we do **not** collect

We want to be specific, because "we respect your privacy" means nothing on its own. Unfolio does not collect, receive, store, transmit, sell, rent, or share any of the following:

- **Your Instagram password.** The app never asks for it, has no field to enter it, and could not use it if you typed it somewhere. Unfolio does not log in to Instagram and does not use the Instagram API. If any app in this category asks you for your Instagram password, do not give it to them.
- **Your name, email address, phone number, or date of birth.** There is no account to create, so there is nothing to fill in.
- **Your follower or following lists.** These are produced on your device and stay on your device.
- **Anything else inside your Instagram export.** Your export may contain your photos, videos, direct messages, comments, likes, search history, contact information, and advertising data. Unfolio reads **none of it**. See Section 5.
- **Your location.** The app does not request location permission and does not use it.
- **Your contacts, photo library, camera, or microphone.** The app does not request access to any of these.
- **Your advertising identifier (IDFA / GAID).** Unfolio does not show ads, does not participate in any advertising network, and does not ask for tracking permission.
- **Analytics or usage data.** There is no analytics SDK in the app. We do not know which screens you open, how long you use the app, or how many imports you run.
- **Crash reports.** There is no crash-reporting SDK in the app. If the app crashes, we do not receive a report unless you choose to tell us about it by email.

**We do not track you across other apps or websites, and we do not sell or share your personal information with anyone for any purpose.**

## 4. What is stored on your device

Unfolio stores a small amount of data locally on your phone, inside the app's private storage area. This is your data, on your hardware. It is not visible to us.

The complete list of what is stored is:

| What | Contents | Why |
|---|---|---|
| **Snapshots** | A random identifier, the date and time of the import, the list of usernames who follow you, and the list of usernames you follow | So you can compare imports over time and see who unfollowed you since last time |
| **Hidden accounts** | Usernames you have chosen to hide, and the date you hid them | So hidden accounts stay hidden across future imports |
| **App preferences** | Your chosen language, whether you have completed onboarding, and your notification settings | So the app behaves consistently between launches |

That is all. Note in particular what is *not* in that table: no full names, no profile pictures, no biographies, no email addresses, no phone numbers, no post content. Unfolio stores **usernames and dates**, and nothing more.

**Backups.** If you have iCloud Backup (iOS) or Google One / Android Backup enabled on your phone, your device may include Unfolio's local data in your own encrypted device backup, in the same way it backs up your other apps. That backup belongs to you and is governed by Apple's or Google's terms, not ours. We have no access to it. You can exclude it by turning off backup for Unfolio in your device settings.

**Deleting it.** You are always in control of this data:

- **Settings → Your data → Delete all data** removes every snapshot and hidden account from your device immediately and permanently.
- **Uninstalling the app** removes all of it as well.

There is no "request deletion by email and wait 30 days" process, because there is no copy of it anywhere else to delete.

## 5. What the app reads from your export — and what it deliberately ignores

Your Instagram export is a large archive containing many files. Unfolio's parser opens the ZIP in memory and looks for exactly two things:

- `followers_1.json` (and any additional numbered follower files)
- `following.json`

From those files it extracts **usernames only**. It does not read, index, copy, or retain profile URLs, timestamps of when a follow happened, or any other field.

Every other file in your export — your photos, your messages, your stories, your saved posts, your login history, your ads data, your personal information file — is never opened. The app has no reason to look at them, so it does not.

If the file you choose is not a valid Instagram export, or is a different format than expected, the app shows you an error and stops. It does not upload the file for us to inspect.

## 6. Notifications

Unfolio can remind you to run a new export so your comparison stays current.

These reminders are **scheduled locally on your device** by the operating system. There is no push notification server. No device token, no advertising identifier, and no message content is transmitted to us or to any third party. The app simply asks your phone to display a reminder at a future time.

Notifications are optional. You can turn them off inside Unfolio, or revoke the permission entirely in your device settings, at any time.

## 7. Third parties

Unfolio uses as few third-party services as it is possible to use and still sell an app on a mobile store. This is the complete list.

### 7.1 Apple and Google

Subscriptions and purchases are handled entirely by the **Apple App Store** or **Google Play**, depending on where you downloaded the app. They are the merchant of record for your purchase.

This means Apple or Google — not us — processes your payment. **We never see and never receive your credit card number, bank details, billing address, or Apple/Google account credentials.** What we can see, through the reporting tools they provide, is aggregate and anonymised sales information: how many subscriptions were sold in a country, and the resulting revenue.

- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)
- [Google Privacy Policy](https://policies.google.com/privacy)

### 7.2 RevenueCat

We use **RevenueCat, Inc.** to check whether your subscription is currently active, and to make "Restore Purchases" work when you reinstall the app or move to a new phone. This is the only part of Unfolio that communicates over the network.

RevenueCat acts as our **data processor**: it handles this information on our instructions and under a data processing agreement, and may not use it for its own purposes.

What RevenueCat receives:

- An **anonymous app user ID** — a random identifier generated on your device. It is not your name, not your email address, and not your Instagram username, and it cannot be traced back to you by us or by RevenueCat.
- The **purchase receipt** from Apple, or the **purchase token** from Google, which proves a valid purchase was made.
- **Basic device information**: device type, operating system and version, and country.
- The **date you last used the app**.

What RevenueCat does **not** receive: your Instagram data, your follower or following lists, your usernames, your snapshots, or anything at all derived from your export. That data never leaves your device, so it is not RevenueCat's to receive.

RevenueCat stores this information on Amazon Web Services infrastructure in the United States. See the [RevenueCat Privacy Policy](https://www.revenuecat.com/privacy).

### 7.3 Instagram and Meta

**Unfolio is not affiliated with, endorsed by, sponsored by, or in any way officially connected to Instagram or Meta Platforms, Inc.** Instagram and Meta are trademarks of Meta Platforms, Inc.

Unfolio does not connect to Instagram, does not use Instagram's API, and has no relationship with Meta of any kind. It only reads a file that Meta gave to *you*.

There is one moment when you leave Unfolio for Instagram: when you tap a username in your results, the app opens that profile in the Instagram app or in your browser. From that moment you are interacting with Meta, and Meta's own privacy policy and terms apply to what happens there. We are not informed that you tapped it and do not record it.

### 7.4 That is the complete list

There are no advertising networks, no analytics providers, no attribution or install-tracking SDKs, no data brokers, and no social media SDKs in Unfolio. The app also does not download fonts, images, or any other assets from the internet at runtime — everything it displays is bundled inside the app itself.

## 8. Legal bases for processing (GDPR)

If you are in the European Economic Area or the United Kingdom, we rely on the following legal bases under Article 6(1) GDPR:

| Purpose | Legal basis |
|---|---|
| Verifying your subscription and providing the paid app to you | **Performance of a contract** — Article 6(1)(b) |
| Preventing fraudulent or invalid purchases | **Legitimate interests** — Article 6(1)(f) |
| Sending you local reminder notifications | **Consent** — Article 6(1)(a), given when you allow notifications, withdrawable at any time |
| Responding to you if you email us for support | **Legitimate interests** — Article 6(1)(f) |

The data held **on your own device** is not processed by us at all — we have no access to it — so it does not require a legal basis on our part.

## 9. Your rights

### 9.1 Everywhere

Because your Unfolio data lives on your own device, you can exercise most privacy rights directly, immediately, and without asking anyone's permission: you can view all of it in the app, export it to a file, and delete all of it from Settings. No request, no waiting period, no verification.

### 9.2 If you are in the EEA or UK (GDPR)

You have the right to request access to, rectification of, or erasure of your personal data; to restrict or object to processing; to data portability; and to withdraw consent at any time without affecting processing already carried out.

In practice, the only personal data we could act on is the subscription record held by RevenueCat, since we hold nothing else. Email us at **afekhasson7@gmail.com** with your request and, if possible, your purchase receipt so we can locate the record. We will respond within 30 days.

You also have the right to lodge a complaint with your national data protection supervisory authority.

### 9.3 If you are in California (CCPA / CPRA)

In the twelve months preceding the date of this policy, the only category of personal information we have collected is **commercial information** (subscription and purchase records) and **identifiers** (an anonymous app user ID), for the business purpose of providing and verifying your subscription.

**We have not sold, and do not sell, personal information. We have not shared, and do not share, personal information for cross-context behavioural advertising.** We do not offer financial incentives in exchange for personal information, and we will not discriminate against you for exercising any privacy right.

You may request to know, delete, or correct your personal information by emailing us.

### 9.4 If you are in Israel

Under the Privacy Protection Law, 5741-1981, you have the right to review information held about you and to request its correction or deletion. Please contact us at the address above.

## 10. International transfers

The only personal data that crosses a border is the subscription information described in Section 7.2, which is processed by RevenueCat in the United States, and the payment information you provide directly to Apple or Google.

Where this involves transferring data from the EEA or UK, the transfer is made under the European Commission's Standard Contractual Clauses, incorporated into our data processing agreement with RevenueCat, together with the supplementary safeguards described in RevenueCat's own privacy documentation.

## 11. Retention

- **Data on your device** is kept until you delete it — either through Settings → Your data → Delete all data, or by uninstalling the app. We cannot delete it for you, and we cannot stop you from deleting it.
- **Subscription records** held by Apple, Google and RevenueCat are retained according to their own policies and the tax and accounting record-keeping periods that apply to us. We keep them only for as long as needed to service your subscription, honour restores, and meet legal obligations.
- **Support emails** you send us are kept for as long as needed to resolve your issue, and then deleted.

## 12. Children

Unfolio is not intended for children under **13**. In countries where local law sets a higher minimum age for consent to data processing — 16 in several EU member states — Unfolio is not intended for anyone below that age.

We do not knowingly collect personal information from children. Because the app requires no registration and collects no identifying information, we have no way to determine a user's age.

If you are a parent or guardian and believe a child has used Unfolio in a way that concerns you, contact us at **afekhasson7@gmail.com**. Note that any data the child produced is stored on that child's device only, and can be removed instantly from Settings or by uninstalling the app.

## 13. Security

Unfolio's security model is simple: **we do not hold your data, so it cannot be taken from us.** There is no database of users to breach, no password file to leak, and no server to compromise. This is the single strongest privacy guarantee an app in this category can offer, and it is the reason the app is designed this way.

Data on your device is stored inside the app's private sandbox, protected by the security of iOS or Android and by your device passcode or biometric lock. Communication with RevenueCat is encrypted in transit using TLS.

Please also protect your Instagram export file itself. It is a sensitive document containing far more than follower lists, and it sits in your Downloads or Files app until you delete it. We recommend deleting it once you have imported it.

No method of storage or transmission is completely secure, and we cannot guarantee absolute security.

## 14. Changes to this policy

We may update this policy — for example, if we add a feature or change a service provider. When we do, we will change the "Last updated" date at the top.

If a change is material — meaning it affects what data is collected or how it is used — we will tell you inside the app before the change takes effect, not quietly. If we ever introduced anything that sent data off your device beyond what is described here, it would require your explicit opt-in. That is a commitment, not a formality.

## 15. Contact

Questions, requests, corrections, or complaints:

**Afek Hasson**
Email: **afekhasson7@gmail.com**

---

*Unfolio is not affiliated with Instagram or Meta Platforms, Inc.*

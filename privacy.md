---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

**App:** DoNotBuy
**Effective date:** 13 May 2026
**Last updated:** 13 May 2026

## 1. Who we are

DoNotBuy ("we", "us", "the App") is an iOS application developed and operated by an individual developer based in Poland (the "Developer"). Contact: **radioideaxp@gmail.com**.

For the purposes of the EU General Data Protection Regulation (GDPR), the Developer is the **Data Controller** for the limited categories of personal data described below.

## 2. TL;DR

- The App is designed to operate **on-device**. We do not run our own backend and we do not collect personal data on our servers.
- Your **location data never leaves your device**. Geofencing is performed entirely locally by iOS.
- We use **Apple's In-App Purchase (StoreKit)** to process subscriptions. Apple — not us — receives your payment information.
- We use **RevenueCat** to manage subscription state. RevenueCat receives a pseudonymous identifier and purchase events on our behalf as a data processor.
- We do not use any advertising SDKs, analytics SDKs, or cross-app tracking.

## 3. Data we process

### 3.1 Data processed entirely on your device (never leaves the device)

| Data | Purpose | Where it stays |
|---|---|---|
| Locations of stores/places you add for geofencing | Trigger local warnings when you approach a place you want to avoid | On your iPhone, in the iOS sandbox |
| Goals, budgets, savings entries, dashboard data | Track impulse purchases you avoided | On your iPhone, in the iOS sandbox (with optional iCloud sync via Apple's encrypted CloudKit, controlled by you in iOS Settings) |
| Notification preferences and app settings | App configuration | On your iPhone |

We **cannot** read, see, transmit, or recover this data. If you delete the App, this data is removed by iOS.

### 3.2 Data processed by Apple (App Store / StoreKit)

When you purchase a subscription:

- Apple processes your payment, Apple ID, and tax/billing information **directly**.
- Apple provides us with an anonymous transaction receipt — we do **not** receive your name, email, payment method, or Apple ID.
- Apple's privacy practices are governed by the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

### 3.3 Data processed by RevenueCat (subscription management)

We use **RevenueCat, Inc.** (USA) as a service provider / data processor to verify and manage subscription state. RevenueCat receives:

- A **pseudonymous app user ID** (an anonymous IDFV-derived identifier — not your name, email, or Apple ID)
- **Purchase events** from StoreKit (product ID, transaction date, price, currency, country)
- **Device metadata** (iOS version, app version, country, language)
- **Subscription status** (active / expired / in grace period / billing retry)

RevenueCat does not receive your location, your goals, your spending data, or any content you create in the App.

- RevenueCat's role: **Data Processor** acting on our documented instructions under a signed Data Processing Agreement.
- Transfers outside the EEA: RevenueCat is US-based. Transfers rely on the **EU Standard Contractual Clauses (SCCs)** as a Chapter V GDPR transfer mechanism.
- RevenueCat's privacy policy: <https://www.revenuecat.com/privacy>.

### 3.4 Data we do NOT collect

We do **not** collect, store, or process:

- Your name, email address, phone number, or postal address
- Photos, contacts, microphone, camera, or health data
- Advertising identifiers (IDFA) — we do not show the ATT prompt
- Analytics, crash reports, or telemetry from third-party SDKs (no Firebase, no Mixpanel, no Sentry, no Google Analytics)
- Any cross-app or cross-site tracking data

## 4. Permissions the App requests

| iOS Permission | Why we ask | Required? |
|---|---|---|
| **Location ("While Using" or "Always")** | To trigger geofencing warnings near stores you want to avoid. Coordinates are evaluated on-device by iOS. | Optional. The App works without it; geofencing features are disabled if declined. |
| **Notifications** | To deliver geofence warnings and goal reminders. | Optional. |

You can revoke any permission at any time in **iOS Settings → DoNotBuy**.

## 5. Legal basis for processing (GDPR Art. 6)

| Processing | Legal basis |
|---|---|
| Operating the App on your device | **Performance of a contract** (Art. 6(1)(b)) — you installed the App and use its features |
| Subscription management via RevenueCat | **Performance of a contract** (Art. 6(1)(b)) — managing your subscription you purchased |
| Sending notifications | **Consent** (Art. 6(1)(a)) — you grant the notifications permission |
| Compliance with Apple's App Store rules | **Legal obligation** (Art. 6(1)(c)) and **legitimate interests** (Art. 6(1)(f)) |

## 6. Data retention

- **On-device data:** stored as long as you keep the App installed. Removed when you delete the App or reset the App's data from iOS Settings.
- **RevenueCat:** retains subscription records as required to manage your active and historical entitlements and for accounting/audit obligations. See RevenueCat's policy for specifics.
- **Apple:** retains transaction history according to Apple's Privacy Policy.

## 7. Your rights under GDPR

If you are in the EEA, UK, or Switzerland, you have the right to:

- **Access** the data we hold about you (Art. 15)
- **Rectify** inaccurate data (Art. 16)
- **Erase** your data ("right to be forgotten") (Art. 17)
- **Restrict** processing (Art. 18)
- **Data portability** (Art. 20)
- **Object** to processing based on legitimate interests (Art. 21)
- **Withdraw consent** at any time (Art. 7(3))
- **Lodge a complaint** with your local supervisory authority. In Poland, this is the **President of the Personal Data Protection Office (UODO)**, <https://uodo.gov.pl>.

To exercise these rights, contact us at **radioideaxp@gmail.com**. Because we do not collect identifying information, in most cases we will need you to provide the pseudonymous identifier we use (visible in the App under **Settings → Support Info**) to locate any data held by RevenueCat on our behalf.

We will respond within **30 days** as required by GDPR Art. 12(3).

## 8. Your rights under CCPA (California residents)

We do **not** sell or share personal information as defined by the CCPA. California residents have the same access, deletion, and correction rights described above and may submit requests to **radioideaxp@gmail.com**.

## 9. Children

DoNotBuy is **not intended for users under the age of 13** (or under 16 in the EEA where local law sets a higher digital-consent age). We do not knowingly collect data from children. If you believe a child has used the App, contact us and we will delete any related data RevenueCat may hold.

## 10. International data transfers

The on-device data does not cross any borders. The only international transfer is the pseudonymous identifier and purchase metadata transmitted to **RevenueCat in the United States**, which is governed by the EU Standard Contractual Clauses signed between us and RevenueCat.

## 11. Security

We rely on:

- **iOS sandboxing** to protect on-device data
- **iOS Data Protection (file-level encryption)** for all files
- **HTTPS / TLS 1.2+** for the RevenueCat connection
- **Apple's StoreKit** for all payment processing (we never see card data)

No method of electronic storage or transmission is 100% secure. We cannot guarantee absolute security.

## 12. Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top will change accordingly. Material changes will be announced in the App. Continued use of the App after a change means you accept the updated policy.

## 13. Contact

For any privacy question or to exercise your rights:

**radioideaxp@gmail.com**

Developer based in Poland. Applicable supervisory authority: UODO (Poland).

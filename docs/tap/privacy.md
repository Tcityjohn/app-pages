---
layout: default
title: Privacy Policy - TAP
---

# TAP Privacy Policy

Last Updated: February 24, 2026

## Overview

TAP is a mobile application developed by **Tree City Design** that helps families negotiate and maintain screen time agreements together. TAP is designed for families with teens ages 9-17. This privacy policy explains what data we collect, how we use it, who we share it with, and what rights you have regarding your information.

By using TAP, you agree to the practices described in this policy. If you are a parent or guardian, you are responsible for reviewing this policy and consenting on behalf of your child before they use the app.

## Data We Collect

### Account Information

- **Email address** — required for authentication and account recovery
- **Password** — stored as a secure hash; we never store or have access to your plaintext password
- **First name and family role** (parent or teen) — used to manage family groups and display names within the app
- **Family group membership** — which family you belong to, managed via invite codes created by the parent

### Photos

- Users (including teens) may upload photos as evidence of completed check-in tasks
- Photos are captured via the device camera or selected from the photo library
- Photos are uploaded to and stored in Supabase Storage
- Photos are only visible to members of your family group

### Push Notification Tokens

- We collect your device's Expo push token to deliver check-in reminders and family activity notifications
- You can disable push notifications at any time in your device's Settings

### Analytics Events

- We collect usage analytics (screens visited, features used, button taps, errors encountered) through a custom analytics system stored in our Supabase database
- **Analytics events are linked to your user_id and are not anonymous.** This allows us to diagnose issues for specific accounts and understand how individual families use the app
- We do not use analytics data for advertising, profiling, or sale to third parties
- Analytics data is used solely to improve the app experience, fix bugs, and understand feature usage

### Crash and Error Reports

- We use **Sentry** to collect crash reports and error diagnostics
- Sentry receives: device model, operating system version, app version, error stack traces, and breadcrumb events leading to the crash
- Sentry does not receive your name, email, photos, or family data

### Subscription and Purchase Data

- We use **RevenueCat** to manage in-app subscriptions and purchases
- RevenueCat receives: an anonymous app user ID, purchase receipts, subscription status, and device platform
- RevenueCat does not receive your name, email, photos, or family data
- Payment processing is handled entirely by Apple; we never see or store your payment card details

### Local Storage

- Your authentication token is stored locally on your device using **expo-secure-store**, which leverages the iOS Keychain for encrypted storage
- This token remains on your device and is not transmitted to third parties

### Data We Do Not Collect

- **No location data** — TAP does not request or collect GPS, IP-based geolocation, or any other location information
- **No advertising identifiers** — We do not use IDFA, ATT, or any ad-tracking frameworks
- **No contacts or address book data**
- **No health or biometric data**

## How We Use Your Data

| Purpose | Data Used |
|---------|-----------|
| Account creation and authentication | Email, password hash, name, role |
| Family group management | Name, role, family membership, invite codes |
| Check-in task verification | Photos uploaded by users |
| Push notification delivery | Expo push token |
| App improvement and bug fixing | Analytics events (linked to user_id), crash reports |
| Subscription management | Purchase receipts, subscription status |

We do not use your data for advertising. We do not sell, rent, or trade your data to any third party.

## Third-Party Services

| Service | Purpose | Data Shared | Privacy Policy |
|---------|---------|-------------|----------------|
| **Supabase** | Backend, authentication, database, file storage | Account data, analytics events, photos, family data | [supabase.com/privacy](https://supabase.com/privacy) |
| **Sentry** | Crash reporting and error diagnostics | Device info, OS version, app version, error traces | [sentry.io/privacy](https://sentry.io/privacy/) |
| **RevenueCat** | Subscription and in-app purchase management | Anonymous user ID, purchase receipts, subscription status | [revenuecat.com/privacy](https://www.revenuecat.com/privacy/) |
| **Expo** | Push notification delivery | Device push token | [expo.dev/privacy](https://expo.dev/privacy) |

We do not share data with any advertising networks, data brokers, or social media platforms.

## Data Storage and Security

- All data is stored on **Supabase** cloud infrastructure (hosted on AWS)
- All data is transmitted over **HTTPS/TLS** encryption
- Passwords are stored as cryptographic hashes using Supabase Auth (bcrypt)
- Authentication tokens are stored locally using iOS Keychain via expo-secure-store
- Photos are stored in Supabase Storage with access restricted to family group members via Row Level Security policies
- Database access is controlled through Row Level Security, ensuring users can only access their own family's data

## Data Retention

- **Account data** is retained as long as your account exists
- **Photos** are retained as long as the associated check-in record exists and your account is active
- **Analytics events** are retained for up to **12 months** and may be aggregated or purged after that period
- **Crash reports** in Sentry are retained according to Sentry's default retention period (90 days)
- **Push notification tokens** are retained as long as your account exists and are removed upon account deletion

When you delete your account, your data is removed as described in the "Account Deletion" section below.

## Account Deletion

You can delete your account from the **Settings** screen within the app. When you delete your account:

- Your user record, profile information, and authentication credentials are **permanently deleted** from Supabase Auth and our database
- Your analytics events associated with your user_id are **deleted**
- Photos you uploaded are **deleted** from Supabase Storage
- Your family group membership is removed; if you are the last member, the family group and its associated pacts are also deleted
- Your Expo push notification token is **deleted**
- RevenueCat retains anonymized purchase history as required for App Store compliance; this cannot be linked back to your identity after account deletion
- Sentry crash reports that were already submitted may persist for up to 90 days but contain no personally identifiable information beyond device metadata

Account deletion is **permanent and irreversible**. We recommend exporting or saving any data you wish to keep before deleting your account.

## Children's Privacy (COPPA Compliance)

TAP is designed for families with teens ages 9-17. We take children's privacy seriously and comply with the Children's Online Privacy Protection Act (COPPA) and similar regulations.

### Parental Consent and Involvement

- **A parent must create the family group first.** Teen accounts are only created after a parent establishes a family and generates an invite code
- By creating a family and sharing an invite code with their teen, the parent provides **verifiable parental consent** for their child's use of TAP and the data collection described in this policy
- Parents maintain oversight of their teen's participation through the app's family dashboard

### Data Collected from Children

We collect the same categories of data from teen accounts as adult accounts, limited to what is necessary for the app to function:

- First name and family role (teen)
- Email address (for authentication)
- Photos uploaded as check-in evidence
- Analytics events (linked to user_id)
- Device crash report data (via Sentry)
- Push notification token (if notifications are enabled)

### How Children's Data Is Used

- Children's data is used **only** to provide the app's core functionality: family groups, pact agreements, check-in tasks, and notifications
- We do **not** use children's data for advertising, profiling, or behavioral targeting
- We do **not** sell or share children's data with third parties for commercial purposes
- We do **not** serve ads of any kind within the app

### Parental Rights

Parents have the right to:

1. **Review** their child's personal information by viewing the family dashboard within the app, or by contacting us at the email below
2. **Request deletion** of their child's account and all associated data by contacting us at **support@treecitydesign.com**, or by having the child delete their own account from the app's Settings screen
3. **Refuse further collection** of their child's data by deleting the child's account
4. **Withdraw consent** at any time by contacting us; we will delete the child's data within 30 days of the request

To exercise any of these rights, parents may contact us at:

**Email:** support@treecitydesign.com

Please include "Children's Privacy Request" in the subject line and provide the parent's account email and the child's first name so we can locate the correct records.

### Age Restrictions

- TAP is intended for families with teens ages 9-17
- We do not knowingly collect data from children under 9
- If we learn that we have collected data from a child under 9 without parental consent, we will delete that data promptly

## User Controls

- **Delete your account** — available in Settings within the app
- **Camera access** — can be revoked in iOS Settings > TAP
- **Photo library access** — can be revoked in iOS Settings > TAP
- **Push notifications** — can be disabled in iOS Settings > TAP
- **Contact us** to request data export, correction, or deletion at support@treecitydesign.com

## International Users and GDPR

TAP is operated from the United States. If you access TAP from outside the United States, your data will be transferred to and processed in the United States.

### For Users in the European Economic Area (EEA), UK, and Other Jurisdictions

If you are located in a jurisdiction with data protection laws (such as the GDPR), you may have additional rights including:

- **Right of access** — request a copy of your personal data
- **Right to rectification** — request correction of inaccurate data
- **Right to erasure** — request deletion of your data (see Account Deletion above)
- **Right to restrict processing** — request that we limit how we use your data
- **Right to data portability** — request your data in a structured, machine-readable format
- **Right to object** — object to our processing of your data
- **Right to withdraw consent** — withdraw consent at any time where processing is based on consent

Our legal basis for processing your data is:

- **Contract performance** — to provide the TAP service you signed up for
- **Legitimate interests** — to improve the app, fix bugs, and ensure security
- **Consent** — for optional features like push notifications and, for children's data, parental consent

To exercise any of these rights, contact us at **support@treecitydesign.com**. We will respond within 30 days.

## Contact

For any privacy-related questions, concerns, data requests, or to exercise your rights under this policy, contact us at:

**Tree City Design**
Email: **support@treecitydesign.com**

For children's privacy requests, please include "Children's Privacy Request" in the subject line.

## Changes to This Policy

We may update this privacy policy from time to time. When we make material changes, we will update the "Last Updated" date at the top of this page. If changes materially affect how we handle children's data, we will notify parents via email or in-app notification and obtain new consent where required.

We encourage you to review this policy periodically.

## Compliance

This policy is designed to comply with:

- Apple App Store Review Guidelines
- Children's Online Privacy Protection Act (COPPA)
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Other applicable privacy regulations

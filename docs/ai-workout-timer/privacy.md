---
layout: default
title: Privacy Policy - AI Workout Timer
---

# AI Workout Timer Privacy Policy

Last Updated: February 9, 2026

## Overview

AI Workout Timer is a mobile application that lets you describe a workout in your own words and get a voice-coached interval timer with personality. This privacy policy explains how our app handles data and respects your privacy.

## Voice Input

- The app uses your device's microphone only when you actively trigger voice input
- Speech is converted to text on-device using iOS speech recognition
- Voice data is processed in real-time and immediately discarded after conversion
- We never have access to your actual voice recordings

## Data Collection

### Workout Text Input

When you describe a workout (via voice or text), the description text is sent to our backend server for AI parsing into a structured workout. This text is processed and immediately discarded — it is not stored on our servers.

### On-Device Data

- **Workout history** is stored only on your device using local storage
- **App preferences and settings** are stored only on your device
- **Subscription status** is managed through RevenueCat (see Third-Party Services)

## Analytics (PostHog)

We use PostHog to understand how users interact with the app:

- We collect anonymous usage data (screens visited, features used)
- We do not collect personal information or voice data
- Analytics help us improve the app experience
- You can opt out of analytics in your device settings

## In-App Purchases (RevenueCat)

We use RevenueCat to process subscription and lifetime purchase transactions:

- Only transaction data necessary for purchase processing is collected
- No personal financial information is stored within the app
- Purchase history is managed through your Apple ID

## Data Storage

All user-generated content (workout history, settings, preferences) is stored locally on your device. We do not maintain user accounts or server-side profiles. Analytics data is collected anonymously by PostHog. Subscription data is managed anonymously by RevenueCat.

## Third-Party Services

| Service | Purpose | Data Collected |
|---------|---------|----------------|
| PostHog | Analytics | Anonymous usage events |
| iOS Speech Recognition | Voice-to-text | None (on-device) |
| RevenueCat | Purchases | Transaction data |
| Vercel backend (Gemini AI) | Workout parsing | Workout description text (not stored) |
| Apple AVSpeechSynthesis | Voice coaching | None (fully on-device) |

## User Controls

- You can delete local app data by uninstalling the app
- You can disable microphone access in iOS Settings
- You can manage subscriptions through your Apple ID

## Children's Privacy

AI Workout Timer does not knowingly collect information from children under 13. The app is designed for general audiences.

## Contact

For any privacy-related questions or concerns, please contact us through the App Store or visit our [Support](./support) page.

## Changes to This Policy

We may update this privacy policy occasionally. The "Last Updated" date at the top indicates when changes were made.

## Compliance

This policy is designed to comply with Apple's App Store guidelines and applicable privacy regulations.

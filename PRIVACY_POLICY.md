# Privacy Policy — The Discipline

**Last updated:** May 1, 2026
**App:** The Discipline (Android, package `com.davidwidx.discipline`)
**Publisher:** Vault Planners

The Discipline is a Stoic alarm and quote app. This policy explains exactly what data the app does and does not handle. The short version: the app does not collect, store, or transmit any personally identifiable information about you to our servers. We do not operate any servers.

## What the app does NOT do

- The app **does not** create user accounts.
- The app **does not** collect or transmit your name, email, phone number, location, contacts, calendar, photos, or any other personal information.
- The app **does not** include analytics SDKs, crash-reporting SDKs, advertising SDKs, or any third-party tracking.
- The app **does not** use the device microphone. The `RECORD_AUDIO` permission is explicitly blocked at the operating-system level.
- The app **does not** use the device camera, GPS, or read your contacts, calendar, or storage outside its own app sandbox.
- The app **does not** send push notifications. Notifications are scheduled locally on your device only.

## Data the app does handle

### 1. Local-only data on your device

The app stores the following on your device using Android's standard app storage. None of it leaves your device:

- Alarm time, repeat schedule, and on/off state.
- Which Stoic quote packs you have purchased.
- Which sound packs you have purchased.
- Your audio playback preferences.
- App settings.

This data is removed when you uninstall the app.

### 2. In-app purchases (Google Play + RevenueCat)

The app offers in-app purchases of additional quote packs and sound packs. When you make a purchase:

- The transaction is processed by **Google Play Billing**, governed by [Google's Privacy Policy](https://policies.google.com/privacy) and [Google Play Terms of Service](https://play.google.com/intl/en_us/about/play-terms/).
- Purchase receipts are validated by **RevenueCat**, a third-party service we use to manage entitlements. RevenueCat receives a randomly-generated anonymous user ID (not linked to any personal information you provide), the purchased product ID, and the purchase receipt from Google Play. RevenueCat's privacy policy is available at [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy).
- We do not see your name, email, payment method, or any other identifying information through this process. We see anonymous transaction counts and purchase aggregates only.

### 3. Text-to-speech (ElevenLabs)

If you enable spoken playback of the daily Stoic quote, the app sends the text of the displayed quote to **ElevenLabs**, a third-party text-to-speech service, to synthesize audio. What is sent:

- The text of the public-domain Stoic quote being read.
- A request identifier.

What is **not** sent:

- Your name, email, device ID, or any identifying information about you.
- Your voice, microphone audio, or any audio captured from your device. (The app does not have microphone permission.)
- Any data about other quotes, your alarms, or your purchase history.

ElevenLabs' privacy policy is available at [https://elevenlabs.io/privacy](https://elevenlabs.io/privacy).

If you do not want to use the spoken-quote feature, simply do not enable it; the app works fully without it.

## Permissions the app requests, and why

| Permission | Why |
|---|---|
| `RECEIVE_BOOT_COMPLETED` | To re-arm your scheduled alarm after a device reboot, so your morning alarm still rings if you restarted the phone overnight. |
| `SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM` | Required by Android to fire alarms at the exact time you set, rather than within a windowed delay. |
| `VIBRATE` | To vibrate the device when the alarm goes off, alongside the alarm sound. |
| `WAKE_LOCK` | To briefly wake the device when the alarm fires so the sound and screen activate. |

Permissions explicitly **blocked** at the OS level: `RECORD_AUDIO`. The app will not access the microphone under any circumstances.

## Children

The Discipline is not directed at children under 13 and does not knowingly collect any data from children. The content (Stoic philosophical quotations from Marcus Aurelius, Seneca, Epictetus, Cato, and Zeno) is suitable for general audiences but is intended for adult readers.

## Changes to this policy

If this policy materially changes, the updated version will be posted at the same URL with a revised "Last updated" date above. Continued use of the app after changes constitutes acceptance of the revised policy.

## Contact

For privacy questions, contact:
**dweatherington@gmail.com**

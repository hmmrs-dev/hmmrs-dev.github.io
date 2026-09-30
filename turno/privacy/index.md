---
lang: en
title: Privacy policy – Turno
description: How the Turno app handles your data.
home_url: /turno/
alt_lang: it
alt_url: /turno/it/privacy/
alt_label: Italiano
privacy_url: /turno/privacy/
privacy_label: Privacy policy
---

# Privacy policy

<p class="updated">Last updated: 30 September 2026</p>

Turno is an Android app to keep score in tabletop games, developed by {{ site.developer }}
("I", "me"). This policy explains what data the app handles and how.

**In short:** Turno has no accounts, no ads and no analytics, and I don't run any servers. Your
games stay on your device, and I have no access to them.

## Data stored on your device

The app stores your games (names, scores, score history and timers), players, player groups, rule
presets, your settings (such as theme and language) and whether Turno Pro is unlocked. All of
this is kept in the app's private storage on your device.

If backup is turned on for your device, Android includes this data in your device backup to your
Google account and in device-to-device transfers, so it can be restored on a new phone. These backups
are managed by Google under your Google account, and I can't access them. You can turn backup off in
your device settings.

## Microphone and voice scoring

Voice scoring (part of Turno Pro) uses the microphone only after you grant the permission, and
only while you're using it. The app passes the audio to your device's speech recognition service
(usually provided by Google), which turns it into text. Depending on your device and its settings,
that service may process the audio on Google's servers, under
[Google's privacy policy](https://policies.google.com/privacy). The app itself doesn't record, store
or send audio anywhere.

The recognized text is interpreted on your device, with Gemini Nano on devices that support it, or
with built-in rules otherwise. Only the resulting score changes are saved.

## Compass mode

Compass mode uses your device's orientation sensors to select the player you point the phone at.
This happens on your device only: the app doesn't ask for or use your location.

## Purchases

Turno Pro is bought through Google Play, which handles the payment entirely: the app never sees
your payment details. The app only asks Google Play whether you bought Pro, to unlock it, including
after a reinstall or on a new device. Purchases are covered by
[Google's privacy policy](https://policies.google.com/privacy).

## Sharing and importing games

When you share a game, the app creates a file with its name, player names, scores and history, and
hands it to the app you pick. It's only sent where you choose. When you open a shared game file, the
app reads it only to import the game.

## Google services used by the app

- **ML Kit**, which runs Gemini Nano on your device. According to
  [Google's ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure), it
  sends diagnostic and usage information to Google: device details (such as manufacturer, model and
  Android version), the app's name and version, installation identifiers, performance metrics, error
  codes and the configured languages. This information is encrypted in transit and is not shared with
  third parties. It doesn't include your voice, the recognized text or your games.
- **Google Play Billing** and **Google Play in-app updates**, which talk to the Google Play Store app
  on your device to handle purchases and app updates.

## What I don't do

Turno doesn't require an account, shows no ads, and has no analytics or tracking. I don't
collect, sell or share your personal data.

## Children

Turno isn't directed at children under 13, and I don't knowingly collect personal data from
anyone, including children.

## Your choices

- You can revoke the microphone permission at any time in your device settings.
- You can delete games, players and presets in the app.
- Uninstalling the app, or clearing its storage in your device settings, deletes all its data from
  your device. Backup copies can be deleted from your Google account's backup settings.

## Your rights

I'm based in the European Union, and I'm the data controller for the only personal data I may
process: what you send me when you contact me, which I use only to reply to you. Under the GDPR you
have the right to access, correct and delete your personal data, and to lodge a complaint with a
supervisory authority, such as the Italian
[Garante per la protezione dei dati personali](https://www.garanteprivacy.it).

## Changes to this policy

If this policy changes, the new version will be published on this page and the date at the top will
be updated.

## Contact

For any question about this policy or your data, write to
[{{ site.contact_email }}](mailto:{{ site.contact_email }}).

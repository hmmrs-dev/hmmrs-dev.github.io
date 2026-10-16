---
lang: en
title: Privacy policy – Turno
description: How the Turno app handles your data.
home_url: /turno/
translations:
  it: /turno/it/privacy/
  de: /turno/de/privacy/
privacy_url: /turno/privacy/
privacy_label: Privacy policy
---

# Privacy policy

<p class="updated">Last updated: 15 October 2026</p>

Turno is an Android app to keep score in tabletop games, developed by {{ site.developer }}
("I", "me"). This policy explains what data the app handles and how.

**In short:** Turno has no accounts, no ads and no analytics, and I don't run any servers. Your
games stay on your device, unless you choose to sync them through a folder, and I have no access to
them.

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

## Sync folders

Sync folders (part of Turno Pro) let players get each other's games through a folder they share.
Each sync folder is a folder of your device that you pick. Whenever you open or leave the app, leave
a finished game or sync by hand, Turno:

- saves your finished games in the folder, the ones of the rulesets and groups you chose for it,
  each as a file with its name, date, ruleset, group name, player names, scores and history;
- adds the games it finds in the folder, saved there by the other players, to the app.

Anyone who can open the folder can read the games in it, such as the players you share it with. If
a cloud storage or sync app keeps a folder of your device in sync, that app uploads its files, under
its own privacy policy.

Turno never deletes the files in a sync folder: a game you delete in the app stays in the folder,
and a sync folder you remove from the app stays as it is, with its files. It only changes the file
of a game when that game changes in the app, so that the change reaches the other players. The list
of your sync folders is kept on your device.

## Feedback and crash reports

If Turno closes unexpectedly, it saves the technical details of the error on your device: the time,
the app version and where in the app's code it happened. They're kept in the app's private storage,
left out of device backups, and the app never sends them anywhere by itself.

When you tap **Send feedback** in the settings, Turno opens your email app with a message to me. It
already includes the app version, the Android version and your device's model and, if Turno closed
unexpectedly, the details of the last error. You can read and change the message before sending it,
or not send it at all: nothing reaches me unless you send it. Once your email app opens, Turno
deletes the saved error from your device.

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
- You can remove a sync folder in the app.
- If you gave an earlier version of Turno access to your Google Drive, you can remove it from your
  [Google Account](https://myaccount.google.com/connections).
- Uninstalling the app, or clearing its storage in your device settings, deletes all its data from
  your device. Backup copies can be deleted from your Google account's backup settings.

## Your rights

I'm based in the European Union, and I'm the data controller for the only personal data I may
process: what you send me when you contact me, which I use only to reply to you and to fix the
problems you report. Under the GDPR you have the right to access, correct and delete your personal
data, and to lodge a complaint with a supervisory authority, such as the Italian
[Garante per la protezione dei dati personali](https://www.garanteprivacy.it).

## Changes to this policy

If this policy changes, the new version will be published on this page and the date at the top will
be updated.

## Contact

For any question about this policy or your data, write to
[{{ site.contact_email }}](mailto:{{ site.contact_email }}).

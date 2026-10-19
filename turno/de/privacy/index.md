---
lang: de
title: Datenschutzerklärung – Turno
description: Wie die App Turno mit deinen Daten umgeht.
home_url: /turno/de/
translations:
  en: /turno/privacy/
  it: /turno/it/privacy/
privacy_url: /turno/de/privacy/
privacy_label: Datenschutzerklärung
---

# Datenschutzerklärung

<p class="updated">Zuletzt aktualisiert: 15. Oktober 2026</p>

Turno ist eine Android-App zum Zählen der Punkte bei Gesellschaftsspielen, entwickelt von
{{ site.developer }} („ich“). Diese Erklärung beschreibt, welche Daten die App verarbeitet und wie.

**Kurz gesagt:** Turno hat keine Benutzerkonten, keine Werbung und keine Analysetools, und ich
betreibe keine Server. Deine Partien bleiben auf deinem Gerät, es sei denn, du synchronisierst sie
über einen Ordner, und ich habe keinen Zugriff darauf.

## Auf deinem Gerät gespeicherte Daten

Die App speichert deine Partien (Namen, Punktestände, Punkteverlauf und Timer), Spieler,
Spielergruppen, Regelvorlagen, deine Einstellungen (wie Design und Sprache) und ob Turno Pro
freigeschaltet ist. All das liegt im privaten Speicher der App auf deinem Gerät.

Wenn die Sicherung auf deinem Gerät aktiviert ist, nimmt Android diese Daten in die Gerätesicherung
in deinem Google-Konto und in Übertragungen von Gerät zu Gerät auf, damit sie sich auf einem neuen
Smartphone wiederherstellen lassen. Diese Sicherungen verwaltet Google in deinem Google-Konto, und
ich habe keinen Zugriff darauf. Du kannst die Sicherung in den Einstellungen deines Geräts
deaktivieren.

## Mikrofon und Punkteeingabe per Sprache

Die Punkteeingabe per Sprache (Teil von Turno Pro) nutzt das Mikrofon erst, nachdem du die
Berechtigung erteilt hast, und nur, während du sie verwendest. Die App übergibt die Audiodaten an
den Spracherkennungsdienst deines Geräts (meist von Google bereitgestellt), der sie in Text umwandelt.
Je nach Gerät und dessen Einstellungen kann dieser Dienst die Audiodaten auf Servern von Google
verarbeiten, gemäß der [Datenschutzerklärung von Google](https://policies.google.com/privacy?hl=de).
Die App selbst zeichnet keine Audiodaten auf, speichert sie nicht und sendet sie nirgendwohin.

Der erkannte Text wird auf deinem Gerät ausgewertet, mit Gemini Nano auf Geräten, die es
unterstützen, sonst mit integrierten Regeln. Gespeichert werden nur die daraus resultierenden
Punkteänderungen.

## Kompassmodus

Der Kompassmodus nutzt die Lagesensoren deines Geräts, um den Spieler auszuwählen, auf den du das
Smartphone richtest. Das geschieht nur auf deinem Gerät: Die App fragt deinen Standort weder ab, noch
verwendet sie ihn.

## Käufe

Turno Pro wird über Google Play gekauft, das die Zahlung vollständig abwickelt: Die App sieht deine
Zahlungsdaten nie. Sie fragt bei Google Play nur ab, ob du Pro gekauft hast, um es freizuschalten,
auch nach einer Neuinstallation oder auf einem neuen Gerät. Für Käufe gilt die
[Datenschutzerklärung von Google](https://policies.google.com/privacy?hl=de).

## Partien teilen und importieren

Wenn du eine Partie teilst, erstellt die App eine Datei mit ihrem Namen, den Spielernamen, den
Punkteständen und dem Verlauf und übergibt sie an die App, die du auswählst. Sie wird nur dorthin
gesendet, wohin du willst. Wenn du die Datei einer geteilten Partie öffnest, liest die App sie nur,
um die Partie zu importieren.

## Sync-Ordner

Mit Sync-Ordnern (Teil von Turno Pro) erhalten Spieler die Partien der anderen über einen Ordner,
den sie gemeinsam nutzen. Jeder Sync-Ordner ist ein Ordner auf deinem Gerät, den du auswählst. Immer
wenn du die App öffnest oder verlässt, eine beendete Partie schließt oder von Hand synchronisierst,

- speichert Turno deine beendeten Partien im Ordner, und zwar die der Regelwerke und Gruppen, die du
  dafür ausgewählt hast, jede als Datei mit Name, Datum, Regelwerk, Gruppenname, Spielernamen,
  Punkteständen und Verlauf;
- übernimmt Turno die Partien in die App, die die anderen Spieler im Ordner gespeichert haben.

Wer den Ordner öffnen kann, kann die Partien darin lesen, zum Beispiel die Spieler, mit denen du ihn
teilst. Wenn eine Cloudspeicher- oder Synchronisierungs-App einen Ordner deines Geräts synchron
hält, lädt diese App seine Dateien hoch, gemäß ihrer eigenen Datenschutzerklärung.

Turno löscht nie Dateien in einem Sync-Ordner: Eine Partie, die du in der App löschst, bleibt im
Ordner, und ein Sync-Ordner, den du aus der App entfernst, bleibt mit seinen Dateien, wie er ist.
Turno ändert die Datei einer Partie nur, wenn sich diese Partie in der App ändert, damit die Änderung
die anderen Spieler erreicht. Die Liste deiner Sync-Ordner wird auf deinem Gerät gespeichert.

## Feedback und Absturzberichte

Wenn Turno unerwartet beendet wird, speichert die App die technischen Details des Fehlers auf deinem
Gerät: den Zeitpunkt, die App-Version und die Stelle im Code der App, an der er aufgetreten ist. Sie
bleiben im privaten Speicher der App, sind von Gerätesicherungen ausgenommen, und die App sendet sie
nie von selbst irgendwohin.

Wenn du in den Einstellungen auf **Feedback senden** tippst, öffnet Turno deine E-Mail-App mit einer
Nachricht an mich. Sie enthält bereits die App-Version, die Android-Version und das Modell deines
Geräts und, falls Turno unerwartet beendet wurde, die Details des letzten Fehlers. Du kannst die
Nachricht vor dem Senden lesen und ändern oder sie gar nicht senden: Bei mir kommt nichts an, solange
du sie nicht abschickst. Sobald sich deine E-Mail-App öffnet, löscht Turno den gespeicherten Fehler
von deinem Gerät.

## Von der App verwendete Google-Dienste

- **ML Kit**, das Gemini Nano auf deinem Gerät ausführt. Laut der
  [Offenlegung der Datennutzung von ML Kit](https://developers.google.com/ml-kit/android-data-disclosure)
  sendet es Diagnose- und Nutzungsinformationen an Google: Gerätedetails (wie Hersteller, Modell und
  Android-Version), Name und Version der App, Installationskennungen, Leistungsmesswerte,
  Fehlercodes und die eingestellten Sprachen. Diese Informationen werden bei der Übertragung
  verschlüsselt und nicht an Dritte weitergegeben. Sie enthalten weder deine Stimme noch den
  erkannten Text oder deine Partien.
- **Google Play Billing** und **In-App-Updates von Google Play**, die mit der App Google Play Store
  auf deinem Gerät kommunizieren, um Käufe und App-Updates abzuwickeln.

## Was ich nicht tue

Turno erfordert kein Konto, zeigt keine Werbung und enthält keine Analyse- oder Tracking-Tools. Ich
erhebe deine personenbezogenen Daten nicht, verkaufe sie nicht und gebe sie nicht weiter.

## Kinder

Turno richtet sich nicht an Kinder unter 13 Jahren, und ich erhebe wissentlich keine
personenbezogenen Daten von irgendjemandem, auch nicht von Kindern.

## Deine Möglichkeiten

- Du kannst die Mikrofonberechtigung jederzeit in den Einstellungen deines Geräts widerrufen.
- Du kannst Partien, Spieler und Vorlagen in der App löschen.
- Du kannst einen Sync-Ordner in der App entfernen.
- Wenn du einer früheren Version von Turno Zugriff auf dein Google Drive gegeben hast, kannst du ihn
  in deinem [Google-Konto](https://myaccount.google.com/connections) entfernen.
- Wenn du die App deinstallierst oder ihren Speicher in den Einstellungen deines Geräts löschst,
  werden alle ihre Daten von deinem Gerät gelöscht. Sicherungskopien kannst du in den
  Sicherungseinstellungen deines Google-Kontos löschen.

## Deine Rechte

Ich bin in der Europäischen Union ansässig und der Verantwortliche für die einzigen
personenbezogenen Daten, die ich möglicherweise verarbeite: die Daten, die du mir schickst, wenn du
mich kontaktierst, und die ich nur verwende, um dir zu antworten und die von dir gemeldeten Probleme
zu beheben. Nach der DSGVO hast du das Recht auf Auskunft über deine personenbezogenen Daten, auf
ihre Berichtigung und Löschung sowie das Recht, Beschwerde bei einer Aufsichtsbehörde einzulegen,
etwa beim italienischen
[Garante per la protezione dei dati personali](https://www.garanteprivacy.it).

## Änderungen dieser Datenschutzerklärung

Wenn sich diese Erklärung ändert, wird die neue Version auf dieser Seite veröffentlicht und das
Datum oben aktualisiert.

## Kontakt

Wenn du Fragen zu dieser Erklärung oder zu deinen Daten hast, schreib mir an
[{{ site.contact_email }}](mailto:{{ site.contact_email }}).

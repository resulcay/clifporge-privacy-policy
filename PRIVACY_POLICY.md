# Clipforge — Privacy policy

Effective 15 October 2026

<!-- The same text as the in-app screen (lib/l10n/app_en.arb, keys `privacy*`).
     test/features/settings/privacy_test.dart fails when the two differ. -->

## The short version

Clipforge edits and converts your videos on your device, and your media never leaves it. There are no accounts, no ads and no tracking. The only thing the app sends is a crash report when something goes wrong, and you can switch that off.

## Your media

Videos, photos, audio and subtitle files you import are copied into the app's private storage on your device so that your projects keep working. Editing, converting and exporting all happen on the device. Nothing is uploaded, and the developer cannot see any of it.

## Permissions

Photos: Clipforge sees only the items you pick in the system picker, and adds a result to your library only when you ask it to. Camera and microphone: used only while you record a clip or a voiceover. Clipforge requests no other access. It uses the network only to send crash reports.

## Diagnostics

The app keeps a small log on your device to help find problems. It holds file names and technical details, never the content of your media. The log leaves your device only if you export it yourself in Settings.

## Crash reports

When Clipforge crashes or runs into an unexpected error, it sends a crash report to the developer through Firebase Crashlytics, a Google service. A report holds what failed in the code (the error type and where it happened, with names and paths removed), the app version, the operating system, the device model, technical details of a running job such as the encoder, and a random identifier of the installation that Crashlytics uses to count how many installations a problem affects. It never holds your media, file names, project names or anything you typed. Google processes the reports for the developer and keeps them for 90 days. You can switch crash reports off in Settings › Diagnostics; reports not sent yet are then deleted. Debug and test builds never send them.

## Your control

Deleting a project, a file or an export removes it from the app's storage. Uninstalling Clipforge removes everything it stored. Backups made by your device may include the app's data, according to your own backup settings.

## Children

Clipforge collects no personal information from anyone, including children. Crash reports hold only the technical details described above.

## Changes and contact

If this policy changes, the new text ships with an app update and its date changes. For questions, use the developer contact on the app's store page.

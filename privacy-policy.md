# Kaptra — Privacy Policy

Last updated: September 24, 2026

This policy covers the Android version of Kaptra.

## In short

- Your documents are stored on your phone. Kaptra never sends them
  anywhere, and does not put them in your phone's Google backup either.
  Scanning, text recognition and PDF creation happen on your phone.
- We have no servers, no accounts and no cloud. As Kaptra's developer, we
  receive no data from you: neither your documents nor how you use the app.
- No ads. No analytics or tracking tools were added to Kaptra.
- Kaptra has no internet permission. The app itself cannot open a network
  connection.
- The scanner and purchases are provided by Google. What these two components
  may send to Google is explained separately below.

## Your documents

The pages you scan, the images made from them, the text recognized on them
and your document names are stored on your phone, in the storage area
reserved for Kaptra. Kaptra does not send this data anywhere.

## Retention and deletion

Your data stays only on your phone, until you delete it.

- When you delete a document it goes to the trash and is permanently deleted
  after 30 days.
- When you uninstall Kaptra, all of Kaptra's data is deleted too. Unless you
  exported them first, your documents cannot be recovered (see "Your phone's
  backup").

Because we hold no data about you, there is no need to request access to,
correction of or deletion of your data; your data is already only with you.

## Security

- Kaptra's data is stored on your phone, in the storage area reserved for
  the app.
- Android isolates this area at the operating system level: other apps
  cannot access it.
- Kaptra does not transfer your data anywhere: it has no servers, and
  without the internet permission it cannot open a network connection. Your
  data leaves the phone only through sharing, exporting or a phone-to-phone
  transfer that you start.

## Scanning and Google Play services

The camera screen and edge detection are not Kaptra's own: they are the
document scanner of Google Play services (Google ML Kit). Google Play
services opens the camera; Kaptra has no camera permission. Scanning happens
on your phone and the scanned pages are handed to Kaptra.

- **Download on first use.** If the scanner is not yet on your phone, Google
  Play services downloads it from Google on your first scan. This needs an
  internet connection once; the download is done by Google Play services, not
  by Kaptra.
- **Google's diagnostic data.** Google states that ML Kit features running
  through Google Play services collect data for diagnostics and usage
  analytics: device information (manufacturer, model, Android version), app
  information (package name, version), a device identifier used for
  diagnostics, performance metrics such as latency, settings such as image
  format and resolution, event types and error codes. The content of the
  scanned document is not on the list Google publishes. This data reaches
  Google through Google Play services on your phone, not through Kaptra, and
  is subject to Google's privacy policy:
  <https://policies.google.com/privacy>. Google's list:
  <https://developers.google.com/ml-kit/android-data-disclosure>.
- **The scanner's part inside Kaptra.** The small component that starts the
  scanner runs inside Kaptra and also produces usage statistics. These cannot
  leave your phone either: Kaptra has no internet permission (see "Text
  recognition").

## Text recognition

Text recognition (Premium) also uses Google ML Kit, but this component runs
inside Kaptra rather than in Google Play services: the recognition model ships
with the app and needs no internet. Recognized text is stored only on your
phone, next to its document.

Google's component produces its own usage statistics and queues them on the
phone to be sent to Google. Because Kaptra has no internet permission, these
statistics cannot leave your phone: Android does not allow an app without
that permission to open a network connection. We verified this on the
release build before publishing.

## Purchases

Premium is a one-time purchase made through Google Play's billing system.
Google Play processes the payment; Kaptra never sees your payment details.
Kaptra only learns that the purchase is complete and stores on your phone
that Premium is unlocked. The purchase is subject to Google Play's terms of
service and Google's privacy policy.

Google's billing library also produces its own usage statistics. As with
text recognition, they cannot leave your phone: Kaptra has no internet
permission, and Android does not allow an app without that permission to
open a network connection. We verified this on the release build before
publishing, too.

## Permissions

Kaptra asks your phone for these permissions only:

- **View network state.** To answer "is there a connection?" before opening
  the scanner: if the scanner has not been downloaded yet and there is no
  connection, Kaptra shows its own explanation instead of Google's error page,
  which has no way out. This permission cannot send data.
- **Google Play billing.** For the Premium purchase.

There is no camera, photos, location, contacts or internet permission.

## Your phone's backup

If your phone's backup is turned on, Android backs up app data to your
Google account. Kaptra puts only its settings in that backup: theme,
language and whether Premium is unlocked. Your documents and recognized text
are not included.

When you move to a new phone with a direct phone-to-phone transfer, your
documents move too. That transfer happens between the two phones and does
not go into the backup in your Google account. On Android 8.1 and earlier
this distinction is not possible, so there documents are not included in
direct transfers either.

To back up your documents, use "Export all documents" in Settings.

## Exporting and sharing

When you share a document or export all documents, the file goes to the
place or app you choose. From there on, that app's or service's terms apply.
The exported backup file is not encrypted: anyone who gets the file can see
the documents in it. Kaptra says so when you export, too.

## Children

Kaptra is not directed at children.

## Changes

If this policy changes, the current version is published on this page and
the date above is updated.

## Contact

Developer: Kaptra

For privacy questions:
[kaptra.support@gmail.com](mailto:kaptra.support@gmail.com)

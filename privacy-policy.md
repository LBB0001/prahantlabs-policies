---
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy — PDF Reader

**Last updated 15 August 2026**

PDF Reader is made by PrahantLabs. The short version: your documents stay on
your phone. The app measures how it is used, and nothing about who you are.

## What is collected

There is no account and no sign-in, and nothing you can be identified by is
collected. No name, no email address, no contacts, no location and no
advertising id.

The app does report how it is used, through Google Analytics for Firebase. That
means:

- Which screens are opened, and which tools are run.
- Whether a tool succeeded, and if it did not, which kind of failure it was — a
  locked document, a scan with no text, a language pack that would not
  download.
- Standard measurement data Firebase adds by itself: a random app-instance id,
  device model, Android version, app version, and the country your connection
  appears to be in.

This exists so a tool that breaks on real documents can be found and fixed
without waiting for someone to write a review about it.

**What is never reported:** the name or contents of any document, any text you
type, any signature you draw, and any photograph you take. The advertising id
is switched off, and no data is used for advertising or personalisation.

## Your documents

Every document you open, merge, split, compress, protect, scan, read or
translate is processed entirely on your device. Your files are never uploaded.
There is no cloud processing in any feature.

Photographs taken with the scanner are handled on the device by Google Play
services and returned to the app as a PDF. The pictures are not sent anywhere.

## Where your files are kept

- `Documents/PDF Reader` in your shared storage, which any file manager can
  open, and which survives the app being uninstalled.
- The app's own storage, which is removed if you uninstall it.

On Android 9 and older the shared folder is not available, and files are kept
only inside the app.

## Permissions

The app holds two permissions, and neither of them is one Android asks you to
approve:

- **Internet** — to download the machine-learning models that translation, text
  recognition and the scanner run on. Google Play services delivers these.
- **Network state** — added by those same libraries, and used to check whether
  a download can proceed.

There is **no storage permission**. Choosing a file goes through the Android
picker, which grants access to only the file you chose, and saving goes through
MediaStore, where Android performs the write on the app's behalf.

There is **no camera permission**. The scanner is a screen belonging to Google
Play services; this app never opens the camera itself.

The app asks for no location, contacts, microphone or notification access, and
sends no notifications.

The advertising id permission that the analytics library would normally add is
removed from the app before it is built.

## When the network is used

To fetch a model from Google the first time a feature needs one — a translation
language pack, a recognition model for a script, or the scanner module — and to
send the usage measurement described above.

Once a model is on the device, that feature works with no connection at all.

Your documents are not part of either. A model comes down, a count of which
tool ran goes up, and nothing you opened or wrote goes anywhere.

## Third parties

The app uses **Google ML Kit** for translation, text recognition and document
scanning. All three run on your device. Google servers are contacted only to
deliver the models.

It also uses **Google Analytics for Firebase**, for the usage measurement
described above.

Both are covered by the [Google Privacy Policy](https://policies.google.com/privacy).
There is no advertising, and no other third party receives anything.

## Children

Nothing collected identifies anyone, of any age, and none of it is used for
advertising or profiling. The app is not directed at children under 13 and asks
them for nothing.

## Changes and contact

If this policy changes, the new version ships with the app update and carries a
new date.

Questions: **prahantlabs@gmail.com**

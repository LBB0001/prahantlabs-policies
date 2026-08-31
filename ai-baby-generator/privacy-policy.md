---
title: Privacy Policy — AI Baby Generator
permalink: /ai-baby-generator/privacy-policy/
---

# Privacy Policy — AI Baby Generator

**Last updated 29 August 2026**

AI Baby Generator is made by PrahantLabs. The short version: the two photos you
choose are sent away to be processed, because that is the only way the app can
work — and they are used for that one request and kept by nobody afterwards.

This app is for entertainment. It does not predict anything.

## What is collected

There is no account and no sign-in. No name, no email address, no contacts, no
location, and no advertising id.

There is **no analytics in this app**. Nothing measures which screens you open
or which buttons you press.

## Your photos

This is the part that matters, so it is stated plainly.

When you tap Create, the two photos you chose are **sent over an encrypted
connection to Cloudflare Workers AI**, which is where the models run. They are
used twice in a single request:

1. To check the photo before anything is generated — that it shows one clearly
   visible adult face, and that it is not explicit or violent.
2. As the reference images the generated picture is built from.

The reply comes straight back to your phone. **PrahantLabs operates no server
of its own for this app, keeps no copy of your photos, and never sees them.**
The processing is performed by Cloudflare under
[Cloudflare's privacy policy](https://www.cloudflare.com/privacypolicy/), and
their published terms for Workers AI state that inputs are not used to train
models.

Before a photo leaves your phone it is **reduced to 480 pixels on its longest
edge**. That is what the model needs, and it means the full-resolution original
never travels.

No face signature, face embedding or biometric template is ever created, stored
or shared by this app.

**Photos of children are refused.** If the check cannot confirm an adult face,
the request stops there and nothing is generated.

## What stays on your phone

Every picture the app generates is written to the app's own private storage,
along with the name you give it and the date. That history is **only on your
device**. It is not backed up to us, not synced, and not visible to anyone else.

Uninstalling the app removes all of it.

**Settings → Delete my data** erases every generated picture and every history
entry immediately, in one tap.

Saving a picture to your gallery, or sharing it, is always something you choose
to do.

## Counting your free creations

The free creations are counted **on your phone**, against a random number the
app makes up for itself the first time it runs. That number is tied to nothing
about you — not your device, not your Google account, not your advertising id —
it is never used for advertising or analytics, and reinstalling the app throws
it away and makes a new one.

## Permissions

- **Internet** and **network state** — to send the request described above.
  Granted at install; Android does not ask you about these.
- **Camera** — only if you choose "Take a photo" instead of picking from your
  gallery. Asked for at that moment, and never at launch. Declining it costs
  you nothing: the gallery route does everything the camera route does.
- **Notifications** — declared so the app can tell you when your free
  creations come back. **Nothing requests it and no notification is sent in
  this version.**
- **Photo library write** — on Android 9 and older only, and only when you tap
  Save. Newer versions of Android need no permission for this.

The app asks for **no location, no contacts, no microphone**, and holds **no
advertising id permission**. Choosing a photo uses the Android photo picker,
which hands over only the picture you picked and gives the app no access to the
rest of your library.

## Consent

Before the first photo is ever chosen, the app shows a screen explaining what
happens to it and asks you to agree. Nothing is uploaded before that.

That agreement can be withdrawn at any time in **Settings → Photo processing
consent**.

## Advertising

There is none. The app shows no ads and contains no advertising SDK.

If that changes, this policy will be updated and the change will ship with the
app version that introduces it.

## Purchases

There are none. The app is free, there is nothing to buy, and no payment
information is ever requested or handled.

## Children

The app is not directed at children and refuses photos of them. Nothing it
collects identifies anyone of any age, and none of it is used for advertising
or profiling.

## Changes and contact

If this policy changes, the new version ships with the app update and carries a
new date.

Questions: **prahantlabs@gmail.com**

# LabelLevel Privacy Policy

**Effective date:** 4 October 2026

**Applies to:** the LabelLevel Android app (`com.hemantky.labellevel`), currently in closed testing

**Who is responsible:** Hemant K Y, an individual developer. Contact: hyhemant155@gmail.com

LabelLevel is an early test version. This policy describes what the app does today, including the parts that are unfinished. It will be updated as features are added.

## The short version

- There are no accounts. We do not collect your name, email, phone number, password, or location.
- The conditions and allergies you select are saved on your phone, with a copy on our server under a random ID that the app creates. They are used only to flag ingredients in products you scan.
- Your scan history (the diary) and your water count and target are saved on your phone only, so they are still there when you reopen the app. They are not kept on our server.
- Barcode lookups go from your phone to Open Food Facts, a public food database.
- There are no ads, no analytics, and no third-party trackers.

## What the app handles

### Health profile (conditions and allergies)

During setup you can select health conditions and allergies. The app uses these selections to flag ingredients in the products you scan. That matching happens on your phone.

Your selections are saved in your phone's secure storage, so they are still there the next time you open the app. A copy is also stored on our server. Since there are no accounts, the app creates a random ID the first time you open it and keeps it in your phone's secure storage. The app sends that ID with every request it makes to our server. The server copy is stored under that ID and nobody else can read it. The ID is random: it is not built from your name, your phone, or anything else about you, and it is not an advertising ID.

You can change your selections at any time from the profile button on the Home screen. Removing one removes it from your phone and from the server copy.

Uninstalling the app or clearing its data discards the random ID and the selections saved on your phone. If you reinstall, you start again with an empty profile.

Uploading medical records is not available in this version.

### Scan history

When you log a scan, the app sends the scan result to our server: the product name and brand, the ingredient list, and which ingredients were flagged against your profile. The server does not store it. Your scan history is saved on your phone only and stays there until you clear the app's data or uninstall.

### Water tracking

Your glass count and daily target are saved on your phone only. The count resets at the start of each day. When you log a glass, the app sends a request with no data in it, which the server ignores.

### Barcode scans

When you scan a barcode, your phone sends the barcode number to Open Food Facts to look up the product. Open Food Facts receives the barcode number and, as with any website request, your IP address. It does not receive your health profile or anything else about you. Their privacy policy is at https://world.openfoodfacts.org/privacy.

### Label photos (not currently active)

Reading ingredients from a photo of a label is not working yet. If you take a label photo in this version, the photo is uploaded to our server and stops there. The server has no connection to Anthropic set up, so the photo is not passed on to anyone. It is not processed or stored, and you get a "coming soon" message.

When this feature is enabled, label photos will be sent to Anthropic's API so the printed ingredient list can be read. This policy will be updated before that happens.

Cooked-dish photos are disabled in the app and are not captured or uploaded.

### Assistant (not currently active)

The assistant is not available in this version. Its screen is locked and no messages can be typed or sent.

### Camera

The app uses the camera to scan barcodes and take label photos. It asks for camera permission the first time you open the Scan screen, and the camera is not used until you allow it. If you say no, the rest of the app still works. Barcode detection happens on your phone. The app does not access your photo library, and it does not record video or audio.

## What we do not collect

- Name, email address, phone number, or password
- Location
- Contacts, photo library, or files
- Advertising ID, or any identifier taken from your device. The only ID is the random one described above.
- Payment details. Subscriptions are not available and no purchase can be made.
- Usage analytics or crash reports

The app does not send notifications.

## Who else is involved

- **Open Food Facts** receives barcode numbers, as described above.
- **Railway** hosts our server. Like any host, it processes the network requests the app makes, which includes your IP address.
- **Anthropic** will receive label photos only once that feature is switched on. It receives nothing today.

We do not sell your data or share it with anyone else.

## Storage and security

- Data travels between the app and our server over an encrypted connection (HTTPS).
- The only thing the server keeps is your health profile, stored under your random ID in a file on the server. It is not additionally encrypted on the server. You can clear it by removing your selections in the app or asking us to delete it.
- The things saved on your phone between sessions are your health profile and the random ID (both in the phone's secure storage); your scan history and your water count and target (in the app's own private storage, which other apps cannot read but which is not separately encrypted); and a copy of a label photo in the app's own cache if you take one. Scan history entries include which of your selected conditions or allergies each product was flagged for.

## Deleting your data

Your scan history and water tracking stay on your phone until you clear them. Clearing the app's data in your phone's settings (Settings, Apps, LabelLevel, Storage, Clear data) or uninstalling the app removes everything on your phone, including the random ID, after which the profile on our server can no longer be reached from any app. The water count also resets by itself at the start of each day.

You can empty your profile yourself: open it from the Home screen, turn off every selection and save. That clears it on your phone and on our server.

To have the server record itself deleted, email hyhemant155@gmail.com. The app does not show you your random ID yet, so tell us which conditions and allergies you selected and roughly when you set the app up. We use that to find your record and delete it. If we cannot single it out, we will tell you.

## Children

LabelLevel is not intended for children under 13.

## Not medical advice

LabelLevel flags ingredients for information only. It does not diagnose, treat, or replace advice from a clinician.

## Changes to this policy

We will update this page when the app changes and change the effective date above.

## Contact

Hemant K Y

hyhemant155@gmail.com

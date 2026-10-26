# LabelLevel Privacy Policy

**Effective date:** 26 October 2026

**Applies to:** the LabelLevel Android app (`com.hemantky.labellevel`), currently in closed testing

**Who is responsible:** Hemant K Y, an individual developer. Contact: hyhemant155@gmail.com

LabelLevel is an early test version. This policy describes what the app does today, including the parts that are unfinished. It will be updated as features are switched on.

## The short version

- There are no accounts. We do not collect your name, email address, phone number, password, or location.
- The conditions and allergies you select are saved on your phone, with a copy on our server under a random ID that the app creates. They are used only to flag ingredients for you.
- A medical report you choose to read is read on your phone and never uploaded. Test results you save from it stay on your phone only.
- Your scan history (the diary) and your water count and target are saved on your phone only, so they are still there when you reopen the app. They are not kept on our server.
- Barcode lookups and swap searches go from your phone to Open Food Facts, a public food database. Your health profile is never sent to it.
- If you use the assistant, your question goes to Anthropic with whichever of your profile, recent scans and scan details you leave switched on. That includes your conditions and allergies unless you switch off both the profile and the scan details, because each scan's flags say which of them it was flagged for.
- Label photos (and, if you take one, a photo of the nutrition table) and photos of cooked dishes go from your phone to our server and on to Anthropic, whose AI reads the printed ingredient list and nutrition table, or names the dish. Only the photo is sent, not your profile or ID. Our server does not keep the photo, and Anthropic deletes it within 30 days unless it is flagged under its usage policy.
- After a scan, each ingredient gets a short plain-English note. Most come from a list built into the app. For an ingredient the list doesn't cover, its name alone goes to our server and on to Anthropic to write a note, which is marked "AI-written". Nothing about you is sent with it.
- There are no ads, no analytics, and no third-party trackers in the app.

## What the app handles

### Health profile (conditions and allergies)

During setup you can select health conditions and allergies from a list. The app uses these selections to flag ingredients in the products you scan. That matching happens on your phone.

Your selections are saved in your phone's secure storage, so they are still there the next time you open the app. A copy is also stored on our server. Since there are no accounts, the app creates a random ID the first time you open it and keeps it in your phone's secure storage. The app sends that ID with every request it makes to our server. The server copy is stored under that ID and nobody else's app can read it. The ID is random: it is not built from your name, your phone, or anything else about you, and it is not an advertising ID.

You can change your selections at any time from the profile button on the Home screen. Removing one removes it from your phone and from the server copy.

Uninstalling the app or clearing its data discards the ID and the selections saved on your phone. If you reinstall, you start again with an empty profile.

### Medical reports

You can have the app read a medical report (a PDF or a photo) and suggest conditions and allergies for your profile, and test results such as HbA1c, cholesterol, vitamin D or calcium with their date. The report is read entirely on your phone, by text recognition built into the app. It is not uploaded to our server or sent to anyone, including Anthropic.

You choose the file through your phone's own file picker, so the app sees only that file. The app makes a temporary copy to read it, and deletes the copy, and any page images it made, as soon as the text has been read. The report's text is not stored.

The app then shows what it found, each with the line of the report it came from, and you say yes, no or not sure to each one. Only the ones you say yes to are added to your profile. Conditions and allergies are saved like the ones you select yourself (on your phone, with a copy on our server under your random ID). The server copy records that each one came from a report, but not which report or what it said. The report line is not saved with them.

If a test result you save is marked high on the report, the app can suggest a related condition (for example high cholesterol for a high cholesterol reading), which is added only if you say yes. If that condition is already on your profile, the app says the report agrees, and you can mark it as backed by the report; the server copy then records that it came from a report.

Test results you say yes to are saved on your phone only, in its secure storage, with the date the report gives. They are not sent to our server, to Anthropic or to anyone else, including with assistant questions. They are listed on your profile screen, where you can remove each one. They do not change how scans are judged. They are used in two ways, both on your phone: if a saved result shows a nutrient as low (for example calcium or vitamin D), a scan can point out when a product is a source of it; and when a condition on your profile came from your report, a flag names the reading as the reason (for example "your report shows total cholesterol 212 mg/dL, above its printed range"). That wording is worked out each time a result is shown and is not saved with the scan.

### Scan history

Every scan result you see is saved to your history as scanned. Marking it as eaten ("I ate this") is a separate step, and only eaten scans count towards today's totals.

Each time a scan is saved or changed, the app sends the entry to our server: the product or dish name and brand, the ingredient list, the verdict, which ingredients were flagged and which of your conditions or allergies each flag was raised for, the nutrition figures (from Open Food Facts for a barcode scan, or from the nutrition table you confirmed for a label photo), whether and when you said you ate it, and the amount, if you chose one. For a cooked dish it also includes the ingredients you ticked and the portion size. The server does not store any of it. Your scan history is saved on your phone only and stays there until you clear the app's data or uninstall.

When you start a scan or ask the assistant a question, the app also tells our server which kind it is (barcode, label photo, dish photo or assistant question), and asks it what your plan allows. These requests carry nothing else, and the server does not store them.

### Water tracking

Your glass count and daily target are saved on your phone only. The count resets at the start of each day. When you log a glass, the app sends a request with no content to our server, which ignores it.

### Barcode scans

When you scan a barcode, your phone sends the barcode number directly to Open Food Facts to look up the product. Open Food Facts receives the barcode number and, as with any website request, your IP address. It does not receive your health profile or anything else about you. Their privacy policy is at https://world.openfoodfacts.org/privacy.

### Swaps

When you tap "Find swaps" on a scanned product, your phone asks Open Food Facts for other products in the same food category that are listed as sold in your country. It then looks up a few of those products by their barcode numbers to check them. Open Food Facts receives the category, the country, those barcode numbers and, as with any website request, your IP address.

The country comes from the region set in your phone's language and region settings. It is not your location: the app does not use GPS and has no location permission. We do not store it or send it to our server.

Checking each product against your conditions and allergies happens on your phone. Your health profile is not sent to Open Food Facts or to anyone else as part of this.

### Label photos

When you take a photo of a label, the app sends the photo to our server, and our server sends it to Anthropic's API. Anthropic's AI reads what is printed (the product name, brand, serving size, ingredient list, the allergen line such as "Contains: milk, soy", any "may contain" statement and the nutrition table) and sends it back as text. If the photo doesn't show the nutrition table, you can take a second photo of just the table; it is sent and kept the same way. Only the photo goes to Anthropic, with a fixed instruction to read the label. Your health profile, your random ID and your scan history are not sent with it. Checking the ingredients against your conditions and allergies happens on your phone afterwards, the same as for a barcode scan.

Our server does not store the photo. It holds it in memory only while the request is being handled.

Anthropic automatically deletes the photo and its reply within 30 days. The exception is a request that Anthropic's automated safety systems flag as breaking its usage policy: that may be kept for up to 2 years, and longer where the law requires. Anthropic's privacy policy is at https://www.anthropic.com/legal/privacy.

The whole photo is sent, so keep only the label in the frame. Avoid capturing faces, documents, screens or anything else you would not want to share.

### Ingredient notes

After a barcode or label scan, each ingredient gets a short note on what it is and what it does in the food. Most notes come from a list built into the app, and nothing is sent for those.

For an ingredient the list doesn't cover, the app sends the ingredient's name to our server, and our server asks Anthropic's AI for a note. Only the names are sent: not the product, your health profile, your random ID or your scan history. Notes written this way are marked "AI-written". Our server keeps each name and its note so it doesn't have to ask again, for anyone. They are not linked to you or to your ID. Anthropic keeps the request for up to 30 days, or up to 2 years if its automated safety systems flag it, the same as for photos.

### Cooked-dish photos

If you photograph a cooked dish, the photo goes to Anthropic the same way as a label photo, with the same retention, and Anthropic's AI suggests up to three names for the dish. It is not asked what is in it. You confirm the name, then choose the ingredients yourself from a list of what the dish usually contains, which is built into the app. Checking those ingredients against your conditions and allergies happens on your phone. You can also type the dish name instead, and then no photo is taken or sent.

### Assistant

The assistant answers questions about food, ingredients and what you've scanned. It does not say whether something is safe or right for you.

When you ask a question, the app sends it to our server, and our server sends it to Anthropic's API along with the earlier messages in that chat and whichever of these you leave switched on above the chat:

- **Profile:** the conditions and allergies you selected. This is health information.
- **Scans and logs:** the sugars in what you marked as eaten today, your water count, and the names and verdicts of your recent scans.
- **Scan details:** for today's scans, and any earlier scan your question names by product, the name, verdict, flags raised and the first ingredients listed. At most 8 scans per question. Each flag is worded as on the result screen, so it names the condition or allergy it was raised for (for example "flagged because you noted a peanut allergy"), even when Profile is switched off. Test results from a report are never sent, so a flag here always says "you noted", not the reading.

Your random ID is not sent to Anthropic. Anything you type is sent as you typed it, so don't include your name or other personal details. Anthropic keeps questions and replies for up to 30 days, or up to 2 years if its automated safety systems flag one as breaking its usage policy, the same as for photos.

Our server does not store your questions or the replies. To limit use during testing, it counts how many questions each random ID asks per day and per month, and keeps only those counts.

### Camera

The app uses the camera to scan barcodes and take label and dish photos. It asks for camera permission the first time you open the Scan screen, and the camera is not used until you allow it. If you say no, the rest of the app still works. Barcode detection happens on your phone. The app does not access your photo library, and it does not record video or audio. When you read a medical report, you choose one file through your phone's file picker, which gives the app that file only.

## What we do not collect

- Name, email address, phone number, or password
- Location
- Contacts or your photo library, or any file other than a report you choose to read (which stays on your phone and is deleted after reading)
- Advertising ID, or any identifier taken from your device. The only ID is the random one described above.
- Payment details. Subscriptions are not available yet and no purchase can be made. The app contains RevenueCat's payment library for later, but it is not started, so it sends nothing.
- Usage analytics or crash reports

The app does not send notifications.

## Who else is involved

- **Open Food Facts** receives barcode numbers and, when you look for swaps, a food category and your country, as described above.
- **Railway** hosts our server. Like any hosting provider, it handles the network requests the app makes, which includes your IP address and, when you take a label or dish photo, the photo on its way to Anthropic.
- **Anthropic** receives the label, nutrition-table and dish photos you take, your assistant questions with the information you leave switched on, and the names of ingredients the app has no note for, as described above.

We do not sell your data or share it with anyone else.

## Storage and security

- Data travels between the app and our server over an encrypted connection (HTTPS).
- The server keeps two things about you on disk: your health profile, and how many assistant questions your random ID has asked this day and month. It also keeps a list of ingredient names and their AI-written notes, which isn't linked to anyone. The profile is stored under your random ID in a file on the server; it is not additionally encrypted on the server. We keep it until you remove your selections in the app or ask us to delete it.
- When a label photo has been read, the text that came back (product name, brand, serving size, ingredient list, allergen line, "may contain" allergens and nutrition table, never the photo) is held in our server's memory so it can be reused for the same product. It is filed under the product's name and brand, not under your ID, and it is cleared whenever the server restarts.
- The things saved on your phone between sessions are your health profile, any test results you saved from a report, and the random ID (all in the phone's secure storage); your scan history and your water count and target (in the app's own private storage, which other apps cannot read but which is not separately encrypted); and a temporary copy of a label or dish photo in the app's own cache if you take one. Scan history entries include which of your selected conditions or allergies each product was flagged for, the nutrition figures, whether you ate it, and the amount you logged. The daily totals and the weekly sugars chart are worked out on your phone from those entries.

## Deleting your data

Your scan history and water tracking stay on your phone until you remove them. Clearing the app's data in your phone's settings (Settings, Apps, LabelLevel, Storage, Clear data) or uninstalling the app removes everything on your phone, including the random ID, after which the profile on our server can no longer be reached from any app. The water count also resets by itself at the start of each day.

You can empty your profile yourself: open it from the Home screen, turn off every selection and save. That clears it on your phone and on our server.

To have the server record itself deleted, email hyhemant155@gmail.com. The app does not show you your random ID yet, so tell us which conditions and allergies you selected and roughly when you set the app up. We use that to find your record and delete it. If we cannot single it out, we will tell you.

## Children

LabelLevel is not intended for children under 13.

## Not medical advice

LabelLevel flags ingredients for information only. It does not diagnose, treat, or replace advice from a clinician.

## Changes to this policy

We will update this page when the app changes what it collects or stores, and change the effective date above.

## Contact

Hemant K Y

hyhemant155@gmail.com

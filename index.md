# LabelLevel Privacy Policy

**Effective date:** 9 November 2026

**Applies to:** the LabelLevel Android app (`com.hemantky.labellevel`), currently in closed testing

**Who is responsible:** Hemant K Y, an individual developer. Contact: hyhemant155@gmail.com

LabelLevel is an early test version. This policy describes what the app does today, including the parts that are unfinished. It will be updated as features are switched on.

## The short version

- There are no accounts. We do not collect your name, email address, phone number, password, or location.
- The conditions and allergies you select, and your diet preference if you choose one (vegetarian, eggetarian, non-vegetarian, Jain or vegan), are saved on your phone, with a copy on our server under a random ID that the app creates. They are used only to flag ingredients for you.
- A medical report you choose to read is read on your phone and never uploaded. Test results you save from it stay on your phone only.
- Your scan history (the diary) and your water count and target are saved on your phone only, so they are still there when you reopen the app. They are not kept on our server.
- Barcode lookups and swap searches go from your phone to Open Food Facts, a public food database. Your health profile is never sent to it.
- If you use the assistant, your question goes to Anthropic with whichever of your profile, recent scans and logs, scan details and report values you leave switched on. Your conditions and allergies are named only while the profile is switched on. With it off, scan details say what each product contains, not which of your conditions or allergies it was flagged for. Report values are off unless you switch them on, and go only while that switch is on.
- Label photos (and, if you take one, a photo of the nutrition table) go from your phone to our server and on to Anthropic, whose AI reads the printed ingredient list and nutrition table. Only the photo is sent, not your profile or ID. Our server does not keep the photo, and Anthropic deletes it within 30 days unless it is flagged under its usage policy. Cooked dishes are never photographed: you type the dish's name.
- If you type a dish the app's own list doesn't have, the dish name alone goes to our server and on to Anthropic, whose AI lists what the dish usually contains. Nothing about you is sent with it.
- After a scan, each ingredient gets a short plain-English note. Most come from a list built into the app. For an ingredient the list doesn't cover, its name alone goes to our server and on to Anthropic to write a note, which is marked "AI-written". Nothing about you is sent with it.
- There are no ads, no analytics, and no third-party trackers in the app.

## What the app handles

### Health profile (conditions and allergies)

During setup you can select health conditions and allergies from a list. The app uses these selections to flag ingredients in the products you scan. That matching happens on your phone.

Your selections are saved in your phone's secure storage, so they are still there the next time you open the app. A copy is also stored on our server. Since there are no accounts, the app creates a random ID the first time you open it and keeps it in your phone's secure storage. The app sends that ID with every request it makes to our server. The server copy is stored under that ID and nobody else's app can read it. The ID is random: it is not built from your name, your phone, or anything else about you, and it is not an advertising ID. You can see it as "App ID" at the bottom of the profile screen.

You can change your selections at any time from the profile button on the Home screen. Removing one removes it from your phone and from the server copy.

Uninstalling the app or clearing its data discards the ID and the selections saved on your phone. If you reinstall, you start again with an empty profile.

### Diet preference

You can choose one diet preference: vegetarian, eggetarian, non-vegetarian, Jain or vegan. It is optional, and you can change or clear it from the profile button on the Home screen. It is saved and stored exactly like your conditions and allergies: on your phone, with a copy on our server under your random ID. The app uses it on your phone to point out ingredients you don't eat (for example "Contains chicken: you chose vegetarian"), to leave such products out of swaps, and to leave such dishes out of the assistant's dish suggestions. It is sent with assistant questions while the Profile switch is on (see "Assistant"). A diet preference can say something about your beliefs (for example, Jain), so choose one only if you're comfortable with that.

### Medical reports

You can have the app read a medical report (a PDF or a photo) and suggest conditions and allergies for your profile, and test results such as HbA1c, cholesterol, vitamin D or calcium with their date. The report is read entirely on your phone, by text recognition built into the app. It is not uploaded to our server or sent to anyone, including Anthropic.

You choose the file through your phone's own file picker, so the app sees only that file. The app makes a temporary copy to read it, and deletes the copy, and any page images it made, as soon as the text has been read. The report's text is not stored.

The app then shows what it found, each with the line of the report it came from, and you say yes, no or not sure to each one. Only the ones you say yes to are added to your profile. Conditions and allergies are saved like the ones you select yourself (on your phone, with a copy on our server under your random ID). The server copy records that each one came from a report, but not which report or what it said. The report line is not saved with them.

If a test result you save is marked high on the report, the app can suggest a related condition (for example high cholesterol for a high cholesterol reading), which is added only if you say yes. If that condition is already on your profile, the app says the report agrees, and you can mark it as backed by the report; the server copy then records that it came from a report.

Test results you say yes to are saved on your phone, in its secure storage, with the date the report gives. They are not sent to our server or anyone else, with one exception you control: if you switch on "Report values" above the assistant chat, they go with each question you ask while it is on (see "Assistant" below). That switch is off every time you open the assistant. They are listed on your profile screen, where you can remove each one. They do not change how scans are judged. They are used in two ways, both on your phone: if a saved result shows a nutrient as low (for example calcium or vitamin D), a scan can point out when a product is a source of it; and when a condition on your profile came from your report, a flag names the reading as the reason (for example "your report shows total cholesterol 212 mg/dL, above its printed range"). That wording is worked out each time a result is shown and is not saved with the scan.

### Scan history

Every scan result you see is saved to your history as scanned. Marking it as eaten ("I ate this") is a separate step, and only eaten scans count towards today's totals.

Each time a scan is saved or changed, the app sends the entry to our server: the product or dish name and brand, the ingredient list, the verdict, which ingredients were flagged and which of your conditions or allergies each flag was raised for, the nutrition figures (from Open Food Facts for a barcode scan, or from the nutrition table you confirmed for a label photo), whether and when you said you ate it, and the amount, if you chose one. For a cooked dish it also includes the ingredients you ticked and the portion size. The server does not store any of it. Your scan history is saved on your phone only and stays there until you remove a scan from it, clear the app's data or uninstall.

When you start a scan or ask the assistant a question, the app also tells our server which kind it is (barcode, label photo or assistant question), and asks it what your plan allows. These requests carry nothing else, and the server does not store them.

### Water tracking

Your glass count and daily target are saved on your phone only. The count resets at the start of each day. When you log a glass, the app sends a request with no content to our server, which ignores it.

### Barcode scans

When you scan a barcode, your phone sends the barcode number directly to Open Food Facts to look up the product. Open Food Facts receives the barcode number and, as with any website request, your IP address. It does not receive your health profile or anything else about you. Their privacy policy is at https://world.openfoodfacts.org/privacy.

### Swaps

When you tap "Find swaps" on a scanned product, your phone asks Open Food Facts for other products in the same food category that are listed as sold in your country. It then looks up a few of those products by their barcode numbers to check them. Open Food Facts receives the category, the country, those barcode numbers and, as with any website request, your IP address.

The country comes from the region set in your phone's language and region settings. It is not your location: the app does not use GPS and has no location permission. For swaps it goes only to Open Food Facts, and we do not store it. (The assistant sends the region code to our server for a different reason, see "Assistant".)

Checking each product against your conditions and allergies happens on your phone. Your health profile is not sent to Open Food Facts or to anyone else as part of this.

### Label photos

When you take a photo of a label, the app sends the photo to our server, and our server sends it to Anthropic's API. Anthropic's AI reads what is printed (the product name, brand, serving size, ingredient list, the allergen line such as "Contains: milk, soy", any "may contain" statement and the nutrition table) and sends it back as text. If the photo doesn't show the nutrition table, you can take a second photo of just the table; it is sent and kept the same way. Only the photo goes to Anthropic, with a fixed instruction to read the label. Your health profile, your random ID and your scan history are not sent with it. Checking the ingredients against your conditions and allergies happens on your phone afterwards, the same as for a barcode scan.

Our server does not store the photo. It holds it in memory only while the request is being handled.

Anthropic automatically deletes the photo and its reply within 30 days. The exception is a request that Anthropic's automated safety systems flag as breaking its usage policy: that may be kept for up to 2 years, and longer where the law requires. Anthropic's privacy policy is at https://www.anthropic.com/legal/privacy.

The whole photo is sent, so keep only the label in the frame. Avoid capturing faces, documents, screens or anything else you would not want to share.

### Ingredient notes

After a barcode or label scan, each ingredient gets a short note on what it is and what it does in the food. Most notes come from a list built into the app, and nothing is sent for those.

For an ingredient the list doesn't cover, the app sends the ingredient's name to our server, and our server asks Anthropic's AI for a note. Only the names are sent: not the product, your health profile, your random ID or your scan history. Notes written this way are marked "AI-written". Our server keeps each name and its note so it doesn't have to ask again, for anyone. They are not linked to you or to your ID. Anthropic keeps the request for up to 30 days, or up to 2 years if its automated safety systems flag it, the same as for photos.

### Cooked dishes

You type the name of a cooked dish, in any language. The app does not take or send a photo of it. You then choose what was in it from a list of what the dish usually contains. Checking those ingredients against your conditions and allergies happens on your phone.

For most dishes the list is built into the app, and nothing is sent. For a dish the app's list doesn't have, the app sends the dish name, as you typed it, to our server, and our server asks Anthropic's AI what that dish usually contains. Only the dish name is sent: not your profile, your random ID, your scan history or anything else about you. The list that comes back is marked "AI estimate: typical ingredients, not confirmed". Our server keeps each dish name and its list so it doesn't have to ask again, for anyone; they are not linked to you or to your ID. Anthropic keeps the request for up to 30 days, or up to 2 years if its automated safety systems flag it, the same as for photos.

### Assistant

The assistant answers questions about food, nutrition, ingredients, what you've scanned and logged, and everyday health questions as they relate to eating. Its answers are general information, not medical advice. It does not diagnose, and it does not tell anyone to start, stop or change a medicine. If you describe an emergency it shows the emergency number, and if you write that you are in distress it shows the Tele-MANAS helpline (14416). When our server recognises either from your words, the app's own fixed reply is shown and your message is not sent to Anthropic. We do not store these messages.

When you ask a question, the app sends it to our server, and our server sends it to Anthropic's API along with the earlier messages in that chat and whichever of these you leave switched on above the chat:

- **Profile:** the conditions and allergies you selected, and your diet preference if you chose one. This is health information. If you ask what to eat, the app also sends a short list of dishes from its own recipe list whose usual ingredients don't match anything on your profile, and the ingredients that do (for example cream or cashew paste), so the answer can suggest dishes. That list is worked out on your phone from your profile.
- **Scans and logs:** what you marked as eaten today, with the amount and its sugars, saturated fat and sodium; the totals for the last seven days and how they compare with an adult's daily reference intakes; how many eaten items had each verdict; your water count; and the names and verdicts of your recent scans.
- **Scan details:** for your two most recent scans, today's scans, and any earlier scan your question names by product: the name, verdict, flags raised, the nutrition figures per 100 g or ml, and the ingredients listed (the whole list for a scan your question names, the first ones otherwise). At most 8 scans per question. Also, any swaps the app has already found for a product this session (product names, figures and their verdict). If you ask what to buy instead of a product, the app looks for swaps first, as "Find swaps" does (see "Swaps"), and sends what it found. With Profile switched on, each flag is worded as on the result screen and names the condition or allergy it was raised for (for example "flagged because you noted a peanut allergy"). With Profile switched off, each flag says only what the product contains (for example "Contains peanut oil"), with no condition or allergy named. Which ingredients were flagged can still hint at what is on your profile.
- **Food options (always, for some questions):** if you ask about digestion, acidity, gas, sleep, energy or hydration, the app adds a short list of everyday foods from its own reviewed list, and what is often reported to make that problem worse. With Profile switched on, foods that would be flagged for your conditions, allergies or diet preference are left out first, on your phone. With Profile off, the full list is sent.
- **Report values:** off unless you switch it on, and off again each time you open the assistant. While it is on, the test results you saved from a report go with each question: the test's name, the value and unit, the range printed on the report, whether the report marked it high or low, and the report's date. This is health information. Our server does not store them or write them to its logs.

The app also sends our server your phone's region code (for example "IN"), from its language and region settings, so the reply can give the right emergency number. It is not your location, it is not stored, and it is not sent to Anthropic.

Your random ID is not sent to Anthropic. Anything you type is sent as you typed it, so don't include your name or other personal details. Anthropic keeps questions and replies for up to 30 days, or up to 2 years if its automated safety systems flag one as breaking its usage policy, the same as for photos.

Our server does not store your questions, the information sent with them, or the replies. To limit use, it counts how many questions each random ID asks per day and per month, and keeps only those counts.

### Camera

The app uses the camera to scan barcodes and take label photos. It asks for camera permission the first time you open the Scan screen, and the camera is not used until you allow it. If you say no, the rest of the app still works. Barcode detection happens on your phone. The app does not access your photo library, and it does not record video or audio. When you read a medical report, you choose one file through your phone's file picker, which gives the app that file only.

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
- **Railway** hosts our server. Like any hosting provider, it handles the network requests the app makes, which includes your IP address and, when you take a label photo, the photo on its way to Anthropic.
- **Anthropic** receives the label and nutrition-table photos you take, your assistant questions with the information you leave switched on (including your saved report values, only while that switch is on), the names of ingredients the app has no note for, and the names of dishes its list doesn't have, as described above.

We do not sell your data or share it with anyone else.

## Storage and security

- Data travels between the app and our server over an encrypted connection (HTTPS).
- The server keeps two things about you on disk: your health profile (conditions, allergies and diet preference), and how many assistant questions your random ID has asked this day and month. It also keeps a list of ingredient names and their AI-written notes, and a list of dish names and their AI-estimated typical ingredients, neither of which is linked to anyone. The profile is stored under your random ID in a file on the server; it is not additionally encrypted on the server. We keep it until you remove your selections in the app or ask us to delete it.
- When a label photo has been read, the text that came back (product name, brand, serving size, ingredient list, allergen line, "may contain" allergens and nutrition table, never the photo) is held in our server's memory so it can be reused for the same product. It is filed under the product's name and brand, not under your ID, and it is cleared whenever the server restarts.
- The things saved on your phone between sessions are your health profile, any test results you saved from a report, and the random ID (all in the phone's secure storage); your scan history and your water count and target (in the app's own private storage, which other apps cannot read but which is not separately encrypted); and a temporary copy of a label photo in the app's own cache if you take one. Scan history entries include which of your selected conditions or allergies each product was flagged for, the nutrition figures, whether you ate it, and the amount you logged. The daily totals and the weekly sugars chart are worked out on your phone from those entries.

## Deleting your data

Your scan history and water tracking stay on your phone until you remove them. Clearing the app's data in your phone's settings (Settings, Apps, LabelLevel, Storage, Clear data) or uninstalling the app removes everything on your phone, including the random ID, after which the profile on our server can no longer be reached from any app. The water count also resets by itself at the start of each day.

To remove a single scan, open it and tap "Remove from history", or press and hold it in Recent scans on the Home screen or in the Diary. The app asks you to confirm first. The entry is deleted from your phone, and if you had marked it as eaten, it no longer counts towards that day's totals or the weekly sugars chart. Our server keeps no scan history, so there is nothing to remove there.

You can empty your profile yourself: open it from the Home screen, turn off every selection and save. That clears it on your phone and on our server.

To have the server record itself deleted, email hyhemant155@gmail.com and include your App ID. It is at the bottom of the profile screen (open it with the profile button on the Home screen), with a Copy button next to it. We use it to find your record and delete it, and we reply to confirm. The App ID is what links the app to your record on our server, so share it only with us. If you no longer have the app, tell us instead which conditions and allergies you selected and roughly when you set the app up; if we cannot single out your record from that, we will tell you.

## Children

LabelLevel is not intended for children under 13.

## Not medical advice

LabelLevel flags ingredients for information only. It does not diagnose, treat, or replace advice from a clinician.

## Changes to this policy

We will update this page when the app changes what it collects or stores, and change the effective date above.

## Contact

Hemant K Y

hyhemant155@gmail.com

Little Moments — Feeding & Sleep Tracker Upgrade

What's included
- New Feeding & Sleep tab with daily and 7-day summaries.
- Breastfeeding logs: left/right/both side and duration in minutes.
- Bottle / expressed breast milk / formula logs: milk type and quantity in ml.
- Solids logs: food name and optional amount (use only when appropriate for your baby's age and your paediatrician's advice).
- Sleep logs: nap or night sleep, start time, end time, and automatic duration calculation (including overnight spans).
- Quick “Log a feed” and “Log sleep” shortcuts.
- Existing Smart Dashboard, Growth, Add a record, History, reminders, profile, backup/restore, mint/cream styling and icon retained.
- Existing localStorage key and data structure retained; existing records are not intentionally migrated, cleared, or overwritten. New fields are added only to newly saved feeding/sleep records.
- Service worker cache updated to little-moments-v5.

IMPORTANT BEFORE UPDATING
1. Open your currently working Little Moments app.
2. Go to Profile & backup → Export backup (JSON).
3. Keep that backup file safe before replacing website files.
4. Do not clear Safari website data or uninstall the app during this update.

Install/update on GitHub Pages
1. Download and unzip this package.
2. Open your GitHub repository: mraghajyothi/little-moments, branch main.
3. Upload the files inside this ZIP directly into the repository root (same level as the existing index.html). Do not upload a containing folder.
4. Replace index.html and sw.js when GitHub asks; keep manifest.webmanifest and icon-512.png.
5. Commit the changes to main and wait for GitHub Pages to publish.
6. Open the site in Safari and refresh. Then close and reopen the installed app.

Data and privacy
- Existing records remain stored locally in the browser on this device. They are not automatically synced to the cloud.
- This update keeps the existing storage key (littleMomentsDataV2). Still, export a JSON backup first as a precaution.
- Reminders appear inside the app; they do not send push notifications or alarms to your phone.
- Feeding and sleep summaries reflect only entries you log. They are personal tracking summaries, not medical targets or medical advice.

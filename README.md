# Iron Log

A weight-lifting tracker that runs as an iPhone home-screen app. Your data is stored only on your phone.

## Features
- 419 exercises across 13 muscle groups, filterable by equipment, plus your own custom exercises
- Log weight (kg) × reps per set, with your previous session shown beside each set
- Warm-up sets, exercise notes, rest timer with sound
- Ready-made routines (Push / Pull / Legs / Upper / Lower / Full Body) that you can edit, or build your own
- Automatic personal records (heaviest weight, best estimated 1RM, most reps)
- Progress charts per exercise, weekly sets per muscle, week streak
- Plate calculator
- Export a full backup (JSON) or every set (CSV for Excel / Google Sheets), and restore from a backup

## Put it on your iPhone (one-time setup)
1. On GitHub, open this repository → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the branch that holds these files and the **/ (root)** folder, then **Save**.
3. After a minute the page shows your address, e.g. `https://<your-username>.github.io/Weight_tracking/`.
4. Open that address in **Safari** on your iPhone → **Share** → **Add to Home Screen**.

On a free GitHub plan, Pages needs the repository to be public. Only the app's code is public; your workouts never leave your phone.

## Keeping your data safe
- Data is saved in the app's storage on the phone. Deleting the home-screen icon deletes the data.
- Use **More → Export backup (JSON)** now and then and save it to Files / iCloud Drive.
- **More → Restore from backup** brings it back on a new phone or after a reset.

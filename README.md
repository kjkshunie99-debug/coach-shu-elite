# Coach Shu Elite — Weekly Action Plan Upgrade

## What's new
- A weekly action plan in the Coach tab based on the most recent 7 calendar days of saved entries.
- Weekly snapshot: days logged, average logged calories, average recorded protein, and exercise minutes.
- Personalised action priorities for logging consistency, calorie pattern, protein, movement, side effects, and weight trend.
- The plan refreshes when a daily entry or goal settings are saved.
- No invented values: missing records are shown as missing and trigger a data-completion action.

## Publish on GitHub Pages
1. Extract the ZIP.
2. Upload all files and folders inside `coach-shu-elite` to the root of your existing `coach-shu-elite` repository.
3. Commit the changes to `main`.
4. Keep GitHub Pages set to `main` and `/(root)`.
5. Refresh the app. The service-worker cache version is bumped to v5.

## Data storage
The app continues using browser Local Storage under the existing key `shu_mounjaro_journey_v2`. Existing records and settings in that same browser profile should remain available. Export a JSON backup before updating as a precaution. Data is not synced to a cloud database.

## Important
This is a behaviour-tracking aid, not a medical device or a substitute for a clinician/dietitian. Calorie and protein estimates are starting estimates. Do not change Mounjaro/tirzepatide dose based on app feedback. Discuss persistent side effects or inadequate intake with your prescriber.

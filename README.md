# Coach Shu Elite — iPhone-friendly Light Edition

A mobile-first personal fitness, nutrition, weight-trend and accountability tracker.

## Included
- Soft lavender, white and mint-green mobile interface.
- Responsive layout and iPhone safe-area spacing.
- Daily weight, meals, calories, protein, water, exercise and active-calorie logging.
- Goal planning and calorie estimates based on profile inputs.
- Weight and calorie trend visualisations.
- Weekly review and action-plan coaching.
- Historical calorie records from 29 Oct–11 Nov 2026.
- Mounjaro journal and side-effect tracking.
- Local browser storage and JSON backup/restore tools (where available in the app).

## Publish to the existing GitHub Pages repository
1. Extract this ZIP.
2. Open the existing `coach-shu-elite` repository.
3. Choose **Add file → Upload files**.
4. Upload the contents of this folder to the repository root, replacing the existing files.
5. Commit to `main`.
6. Keep Pages configured to `main` and `/(root)`.
7. Open `https://kjkshunie99-debug.github.io/coach-shu-elite/` and refresh.

## Data storage and safety
This version uses browser Local Storage, not a cloud database. Data is specific to the browser profile and device and does not automatically sync across devices. Export a JSON backup before updating or clearing browser data. Never commit personal health backups into this public repository.

Calorie and protein estimates are planning estimates, not medical prescriptions. Do not use the app to independently change prescribed medication doses. Discuss persistent side effects, vomiting, dehydration, or very low intake with your clinician.

## iPhone note
The site is accessible in Chrome on iPhone. For an app-like Home Screen shortcut on iPhone, Safari's **Share → Add to Home Screen** is generally the most reliable route. iOS browsers use WebKit and may have different PWA installation behaviour from desktop/Android Chrome.

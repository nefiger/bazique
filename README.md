# Bazique 2026 Feedback Dashboard

Static dashboard for Bazique 2026 post-event feedback across guest and vendor surveys.

Live URL: pending GitHub Pages deployment

## Data

- Source data was cleaned from two local survey exports.
- Direct identifiers were removed before dashboard work began.
- Guest rows 2 and 3 from the original spreadsheet were excluded as confirmed internal/test responses.
- No additional email addresses or phone numbers were found in open-text fields after cleaning.

## Project

- `index.html` contains the full dashboard app shell and interactivity.
- `assets/style.css` contains all visual styling.
- `data/guest_clean.json` and `data/vendor_clean.json` are the only committed data sources used by the dashboard.

## Notes

- This repository does not include the raw `.xlsx` source files in git.
- Report links in the dashboard are placeholders until the final PDF or DOCX report files are supplied.

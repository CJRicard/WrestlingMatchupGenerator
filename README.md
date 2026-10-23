# Wrestling Matchup Generator

Offline HTML utility for coaches running wrestling events with one or more schools.

## What this does

- Imports wrestler rosters from one or many CSV/TXT files
- Supports manual wrestler entry/edit/delete
- Generates matchup rounds with weight-first logic and configurable constraints
- Tracks unmatched wrestlers and suggests close alternatives
- Supports manual adjustments (create manual matchup, replace one side, lock/unlock, notes)
- Exports final results to CSV and print/PDF

## Files

- `wrestling-matchup-generator.html` — main application (single-file, no install required)
- `wrestling-matchup-generator-user-guide.html` — full instructional documentation with screenshots
- `wmg-01-setup.png` to `wmg-06-export.png` — guide screenshots

## Quick start

1. Open `wrestling-matchup-generator.html` in a modern browser.
2. Go through tabs in order:
   - Event Setup
   - Import or Add Wrestlers
   - Wrestler Roster
   - Matching Settings
   - Matchups
   - Export Final Matchups page
3. Export final outputs from tab 6 (CSV or PDF).

## Data format for import

Expected columns (header order can vary):

`firstname,lastname,weight,agelevel,experience,school,desiredmatches`

Experience values:
- `Beginner`
- `Intermediate`
- `Advanced`

## Notes

- All processing is local in the browser.
- Data persists in browser local storage until cleared.
- Use **Clear All Data** in the app to reset.

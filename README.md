# Dem Leader Support-o-Meter

Tracks public, on-record statements by congressional Democrats on their leaders, scored -5 (outright opposition) to +5 (vocal support), with simple and seniority-weighted averages. A selector at the top switches between the two races.

- `index.html` - the page
- `house.json` - Hakeem Jeffries as House speaker
- `senate.json` - Chuck Schumer as Senate majority leader

Each data file holds its own labels, "through" date, notes, method and one row per member (`name, state, status, years, weight, score, basis`).

Scores are a judgment of press-reported statements, not a vote prediction.

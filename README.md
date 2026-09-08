# American Golf Atlas

Interactive map of U.S. golf courses — state leaderboards cross-referenced with national Top 100 lists.

**Live site:** https://mktcowboy.github.io/american-golf-atlas/

## Features
- Imagery / dark / light basemaps (free tiles, no API keys)
- ★ Top 100 USA (Golf Digest 100 Greatest + GOLF Top 100)
- Best in State = #1 course per state
- Regional lists (Texas Top 50, Florida Top 50, Colorado Top 50, Southern states, …)
- Ranked table view with **Table only** mode, CSV export
- **[History](history.html)** — archived Golf Digest & GOLF Magazine Top 100 tables by edition

## Map vs History
- The **map** (`index.html`) shows **current editions only**: Golf Digest America’s 100 Greatest **2025-26**, GOLF Magazine Top 100 US **2024-25**, plus GDBIS 2025-26 and state/regional lists.
- The **History** page does not change map ranking or UI — it is a standalone archive of prior biennial Top 100 lists (CSV + embedded tables).

## Data sources (personal research)
- Top100GolfCourses state leaderboards
- Golf Digest Best in State / America’s 100 Greatest
- GOLF Magazine Top 100 Courses in the U.S.
- Golfweek Best Public / Private by state
- OpenGolfAPI directory (ODbL 1.0)
- Addresses/coords via public web + OpenStreetMap Nominatim
- Historical Top 100: official golfdigest.com / golf.com story pages when available; Planet Golf archives otherwise (`data/history/`)

Rankings are included for personal research use. Obtain permission before commercial redistribution.

## Local preview
Open `index.html` or `history.html` in a browser, or:

```bash
python3 -m http.server 8080
```

## GitHub Pages
Settings → Pages → Deploy from branch `main` / folder `/ (root)`.

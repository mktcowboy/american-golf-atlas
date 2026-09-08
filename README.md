# American Golf Atlas

Interactive map of U.S. golf courses — state leaderboards cross-referenced with national Top 100 lists.

**Live site:** (GitHub Pages URL after deploy)

## Features
- Imagery / dark / light basemaps (free tiles, no API keys)
- ★ Top 100 USA (Golf Digest 100 Greatest + GOLF Top 100)
- Best in State = #1 course per state
- Regional lists (Texas Top 50, Florida Top 50, Colorado Top 50, Southern states, …)
- Ranked table view with **Table only** mode, CSV export

## Data sources (personal research)
- Top100GolfCourses state leaderboards
- Golf Digest Best in State / America’s 100 Greatest
- GOLF Magazine Top 100 Courses in the U.S.
- Golfweek Best Public / Private by state
- OpenGolfAPI directory (ODbL 1.0)
- Addresses/coords via public web + OpenStreetMap Nominatim

Rankings are included for personal research use. Obtain permission before commercial redistribution.

## Local preview
Open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
```

## GitHub Pages
Settings → Pages → Deploy from branch `main` / folder `/ (root)`.

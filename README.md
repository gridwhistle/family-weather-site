# Family Weather site

The public pages for Family Weather: Side by Side, served by GitHub Pages from the root of `main`.

- `/` landing page
- `/privacy/` privacy policy (linked from the app's Plus screen and App Store Connect)
- `/support/` support page (App Store Connect support URL)
- `/compare-weather-two-cities/`, `/weather-where-your-parents-live/`, `/long-distance-family-ideas/` articles
- `sitemap.xml` lists every page; add new pages to it
- `og-image.png` (1200x630) is the link preview image; `images/` holds screenshots cut from the 1.1 app preview

App Store links carry `data-ct="site-..."` naming where they sit, so campaign tokens can be added in one pass once the provider token is known.

Plain HTML and one stylesheet, no build step. `.nojekyll` keeps GitHub Pages from running Jekyll.

## Before publishing

- The home page body and the three articles describe 1.1 (iPad, Apple Watch, the radar in the US and Canada, the Harvest theme) and link to the App Store. Publish them only once 1.1 is Ready for Distribution. The Harvest bullet in `long-distance-family-ideas/` carries a note on when to cut it.
- If an article goes out after November 13, 2026, set its `datePublished`, `dateModified` and `article:published_time` to the real day.
- Google's Rich Results Test marks the home page's Software App item invalid ("Either aggregateRating or review should be specified"). That is expected until the app has real App Store ratings. Never add ratings or reviews by hand.

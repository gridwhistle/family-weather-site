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

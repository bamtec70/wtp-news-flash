# We The People Press News Flash

Each alert lives in its own folder: `/YYYY-MM-DD-short-slug/`.

## Add a new alert
1. Copy `_template/index.html` to `NEW-SLUG/index.html` (e.g. `2026-11-02-some-story`).
2. Replace every placeholder: `{{HEADLINE}}`, `{{DESCRIPTION}}` (one factual sentence), `{{SLUG}}` (folder name), `{{DATE}}` (e.g. NOV 2, 2026), `{{STORY}}` (full article HTML below the flash: kicker, `<h2>` headline, `<p>` paragraphs, `<h3>Sources</h3>` list of verified links; 300-500 words, no em dashes; the template already appends "You decide what to trust."). The "Read full story" button scrolls to `#story`.
3. Add `NEW-SLUG/og.png` (1200x630 screenshot of the flash) and `NEW-SLUG/NEW-SLUG.mp4` (H.264 + AAC).
4. Add a `<li>` to the top of the list in root `index.html`.
5. Commit and push. URL: `https://bamtec70.github.io/wtp-news-flash/NEW-SLUG/`

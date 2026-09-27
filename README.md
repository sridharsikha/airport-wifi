# Before You’re Online

A responsive, static microsite comparing Wi-Fi onboarding at Delhi, Hyderabad, Singapore Changi, San Francisco, London Heathrow, Dubai International and Ben Gurion.

## Preview

Open `index.html` in a browser. The site uses local files only, works without JavaScript, and needs no installation, account, API key or build step. External source links require internet access.

## Publish on GitHub Pages

1. Extract the ZIP on your computer.
2. Create a GitHub repository, for example `airport-wifi`. Use a public repository for the usual free GitHub Pages route.
3. Upload the **contents** of this folder to the repository’s root. `index.html` must be at the top level, not inside an extra `airport-wifi` folder. Include `styles.css`, `sources.json` and `.nojekyll`. You may omit `linkedin-post.md` and `QA.md` from the public repository.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then **Save**.
6. Wait for the Pages deployment to complete. GitHub shows the published URL in Settings → Pages. A project repository normally appears at `https://YOUR-USERNAME.github.io/airport-wifi/`.

For a user site, name the repository `YOUR-USERNAME.github.io`; its URL is `https://YOUR-USERNAME.github.io/`.

Repository: https://github.com/sridharsikha/airport-wifi
GitHub Pages address: https://sridharsikha.github.io/airport-wifi/

Official guide: [Configure a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Files

- `index.html` — complete site, including source citations and original journey diagrams.
- `styles.css` — responsive layout, focus states, reduced-motion support and print styling.
- `sources.json` — downloadable source notes and airport-specific evidence classifications.
- `.nojekyll` — serves the static files without Jekyll processing.



## Editorial notes

Sources were reviewed on 27 September 2026. This is a published-instructions review, not an on-site network test. Current accessibility of a page does not establish when it was updated.

Delhi and Hyderabad have documented passport alternatives to their phone-code routes. Hyderabad lists a country-code selector; it is not classified as Indian-number-only. Neither cited Wi-Fi page lists a boarding pass. Heathrow explicitly requires registration but leaves the fields unspecified.

Dubai’s one-click claim is labeled historical (official announcement, 14 March 2017). Ben Gurion’s no-registration claim is labeled unofficial and unverified. Do not remove those qualifiers without new evidence.

All visuals are original explanatory diagrams, not airport portal screenshots. Airport names identify the subjects of comparison; no affiliation is implied. Third-party screenshots, logos and photographs are not included. Official Hyderabad kiosk photos are linked at their source instead of copied.

## Updating the site

Edit the relevant airport card and table row in `index.html`, then update the corresponding entry in `sources.json`. Keep the visible dates and source notes consistent. Verify the new source’s actual claim; do not replace “not listed” with “not required” without evidence. The JSON is a companion record, not a live data feed.

All local links are relative so the site works at both a GitHub Pages root and a repository subpath. There are no external fonts, libraries, trackers, cookies or remote image dependencies.

# Govee Meta Deep-Dive

Static one-page report, deployed on Vercel. No build step: `index.html` is served as-is.

- `index.html`: the report (design system from the Rosabella / Solawave deep-dive template)
- `data/govee_ads.tsv`: all 190 ads on record for Govee's Meta page (Atria, as of 3 Mar 2026), used for every count on the page

Pending: section 05 (fill the `likes` array from an AdSpy capture) and landing-page captures in section 10.

Deploy: import this repo in Vercel (Framework preset: **Other**, no build command, output directory `.`), or run `npx vercel --prod` from the repo root.

# The Layered Political Test

A single-page, no-dependency quiz that scores you on 14 separate traits across 7 layers (structure, economy, social order, values, time, methods, scope) and matches your full profile against 32 ideologies and government forms.

Everything runs in the browser. No data is collected or sent anywhere.

## Run locally

Open `index.html` in a browser.

## Host on GitHub Pages

1. Create a new repository and add `index.html` and `README.md`.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute your test will be live at `https://<your-username>.github.io/<repo-name>/`.

## Customize

All content is in `index.html`:

- `D` lists the 14 traits and their two poles.
- `Q` lists the statements as `[trait index, direction, text]`.
- `I` lists ideology profiles as 14 values from 0 to 100, in the same order as `D`.

Add or edit entries in `I` to include more ideologies.

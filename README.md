# Thai Stock Portfolio Dashboard

A lightweight, responsive, browser-based portfolio tracker for six Thai stocks: SCB, PTT, GULF, TTB, CPALL and OSP.

## Features
- THB portfolio market value, total cost and profit/loss calculations
- Editable share quantities and latest prices
- Average cost basis prefilled from the owner's supplied figures
- Portfolio allocation chart
- Save up to 60 portfolio snapshots for a history chart
- Export holdings to CSV
- Local browser storage; no server or API key required

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Open the repository's **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then click **Save**.
5. Wait for GitHub Pages to publish the site. The Pages URL will appear in Settings > Pages.

## Important data notes
- Latest prices are entered manually; this project does not currently connect to a live market data provider.
- Share quantities start at zero and should be entered by the user.
- Holdings and snapshots are saved in the current browser's local storage. They do not sync across devices.
- This is a tracking tool, not investment advice.

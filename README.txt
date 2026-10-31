JAFAR RISK CALCULATOR — SETUP

CONTENTS
- index.html: calculator
- manifest.json: installable app information
- sw.js: offline cache
- icon.svg: app icon

PUBLISH FREE WITH GITHUB PAGES
1. On a computer or phone browser, sign in to GitHub (github.com).
2. Create a new PUBLIC repository named jafar-risk-calculator.
3. Upload all four app files (index.html, manifest.json, sw.js, icon.svg) to the repository root.
4. Open the repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Choose branch main and folder /(root), then Save.
7. Wait for GitHub Pages to publish. It will show your website address.
8. Open that HTTPS address in Chrome on Android.
9. Open Chrome's three-dot menu and choose Install app or Add to Home screen.

IMPORTANT
- The app uses only three trade inputs: risk, entry, stop-loss.
- LONG/SHORT is inferred from stop-loss relative to entry.
- Margin is shown at 5x, 10x and 20x; no leverage input is needed.
- Position sizing is for linear USDT-margined contracts.
- Fees, slippage, funding and exchange-specific contract rules are not included.
- Always compare with your exchange's order preview before placing a trade.
- For reliable PWA installation and offline use, host it on HTTPS (GitHub Pages provides HTTPS).

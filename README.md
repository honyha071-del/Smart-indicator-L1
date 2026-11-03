# GOLD PULSE PRO — XAUUSD Dashboard

A static, mobile-friendly XAUUSD market dashboard for GitHub Pages.

## Deploy to GitHub Pages
1. Create a new GitHub repository (for example `gold-pulse-pro`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open the URL shown in Settings → Pages.

## Data and limitations
- Chart, technical analysis, economic calendar, and symbol news are embedded from TradingView widgets.
- Data availability, delay, symbol coverage, and widget behavior are controlled by TradingView and the selected data provider.
- Forex Factory is linked directly. This static site does not scrape Forex Factory or claim to use an official Forex Factory API.
- No API keys or backend are included. GitHub Pages hosts static files only.
- No automatic BUY/SELL execution or guaranteed signal is provided. The checklist is educational.

## Customize
Edit `index.html`. The chart currently uses `OANDA:XAUUSD`. If that symbol is unavailable for your region/account, change the `"symbol"` values to a supported TradingView XAUUSD symbol.

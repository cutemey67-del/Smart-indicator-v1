# Gold Pulse — XAUUSD Dashboard

A GitHub Pages starter dashboard in Khmer featuring:
- TradingView XAUUSD chart (OANDA feed)
- TradingView technical-analysis widget
- US economic calendar widget
- Direct links to Forex Factory calendar and news

## Run locally
Open `index.html` in a modern browser. Internet access is required for the embedded TradingView widgets.

## Publish on GitHub Pages
1. Create a new public GitHub repository, for example `gold-pulse`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then Save.
6. Wait for the Pages URL to appear.

## Important data limitation
Forex Factory does not provide a generally available, unrestricted public API for this use. This starter links to Forex Factory instead of scraping it. The embedded TradingView economic calendar is a separate source, not Forex Factory data. For automatic Forex Factory-like event ingestion, connect a licensed calendar API (for example, a provider with an API key) through a small backend/serverless function. Do not expose private API keys in a public GitHub repository.

## Notes
- The chart symbol is `OANDA:XAUUSD`; the quote can differ slightly from another broker.
- Widgets require internet access and may be delayed depending on the data provider.
- Technical ratings are indicators, not guaranteed buy/sell instructions.

# Deriv Analyzer

Live digit analysis for Deriv synthetic indices (and related markets).

## Features

- Live price feed and last-digit highlight
- Interactive chart (line / candles, multiple timeframes)
- Digit analysis over a configurable tick window:
  - Even / Odd
  - Over / Under
  - Rise / Fall
  - Match / Differ
  - Digit frequency (0–9)
- Dark custom market picker
- Responsive layout (desktop + mobile)
- Analysis only — no trading / account connection

## Run locally

Open `index.html` in a browser, or serve it:

```bash
# Python
python3 -m http.server 8080

# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Markets

Volatility, Volatility (1s), Boom/Crash, Step, Jump, Drift Switch, Forex & Crypto (via Deriv public ticks feed).

## License

Use freely for personal analysis. Not affiliated with Deriv.

# Volatility Modeling of BTC and S&P 500

This project studies the determinants and persistence of price volatility
in cryptocurrency (Bitcoin) and equity markets (S&P 500) using
GARCH-family models.

## 📄 Report
- **Full paper (PDF):**
  - `Volatility-Modeling-of-BTC-and-S&P500.pdf`

## 🔍 Research Question
- Is volatility predictable despite Random Walk Theory?
- Does volatility dynamics remain consistent across assets and time?

## 🧠 Methodology (High-level)
- Daily returns of BTC and S&P 500
- GARCH(1,1), GARCH-t, ARMA-GARCH, GARCH-X
- Diagnostic tests:
  - Ljung-Box
  - ARCH LM
  - Nyblom stability
  - Sign Bias tests
- Rolling-window estimation (2005–2024)

## 📊 Key Findings
- Strong volatility clustering in both markets
- High persistence (α + β ≈ 1)
- BTC exhibits higher absolute volatility
- Relative volatility dynamics are similar after standardization
- Macroeconomic variables do not significantly improve volatility forecasts

## 🧩 Notes
- Original R Markdown file is unavailable.
- This repository focuses on documenting the research results and methodology.

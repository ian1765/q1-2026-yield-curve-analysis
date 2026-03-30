
# Q1 2026 Yield Curve Analysis
![Spread Chart](Q1_2026_Spreads.png)

This project analyzes the U.S. Treasury yield curve during Q1 2026 using:

- Yield curve shape analysis
- Spread decomposition (10Y–2Y, 10Y–3M, 2Y–3M)
- PCA (Level, Slope, Curvature)

## Key Findings

- The curve was not structurally inverted
- A front-end inversion (2Y–3M) reversed during the quarter
- Long-end spreads remained positive throughout
- PCA shows:
  - Level (~81%) → dominant driver
  - Slope (~16%) → front-end normalization
  - Curvature (~2%) → minimal impact

## Interpretation

Q1 2026 reflects a transition from localized front-end dislocation to a fully normalized yield curve, where short-term expectations realigned with the broader term structure.

## Files

- `notebook.ipynb` → full analysis
- `report.pdf` → summarized research note

## Tools

- Python (Pandas, Matplotlib, Scikit-learn)
- Data: FRED (Federal Reserve Bank of St. Louis)

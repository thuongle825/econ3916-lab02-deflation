# econ3916-lab02-deflation
Deflating Economic Data — Nominal vs. Real

Objective
This project quantifies the divergence between nominal and inflation-adjusted economic indicators by constructing a CPI-based deflation pipeline and applying it to U.S. wage and price data.

Methodology
Retrieved CPI and average hourly earnings series directly from FRED (no API key required)
Implemented a reusable deflation function to convert nominal series into constant 2020 dollars
Applied the deflator to both wage data and Big Mac pricing to enable cross-metric comparison
Developed an interactive base-year slider to let users re-anchor the real-dollar conversion on demand
Key Findings
Nominal average hourly earnings rose from $2.50 to $32.53, but in real (2020) terms the gain was far more modest — from $20.92 to $25.20
The U.S. Big Mac price climbed 178% in nominal terms, yet only 43% in real terms, against 95% cumulative CPI inflation over the same period
The gap between nominal and real growth rates across both series underscores how headline figures overstate purchasing-power gains absent an inflation adjustment

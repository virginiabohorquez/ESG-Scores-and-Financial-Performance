# ESG-Scores-and-Financial-Performance
Final Python Project

# ESG Scores vs Stock Performance

This question explores whether companies with higher ESG (Environmental, Social, Governance) scores tend to have better stock performance, measured in terms of returns and volatility.

## Research by: Virginia Bohorquez

---

## Research Question
Do companies with higher ESG scores tend to have better stock performance (e.g., returns, volatility)?

---

## Data Sources
- **ESG Dataset**: Contains Environmental, Social, and Governance scores for a large set of companies.
- **Yahoo Finance**: Used via the `yfinance` Python library to pull 1 year of historical stock data.

---

## Methodology
1. Cleaned ESG data and matched tickers.
2. Pulled stock prices using `yfinance`.
3. Calculated average monthly returns and volatility for each company.
4. Merged the ESG scores with performance metrics.
5. Analyzed relationships using correlation matrix and scatter plots.

---

## Key Findings
- No strong correlation between ESG scores and monthly returns.
- Slight negative correlation between ESG scores and volatility: higher ESG = more stable stock behavior.

---

## Discussion
- **Limitations**: Short time window (1 year), and only return/volatility used as performance proxies.
- **Future Work**: Industry breakdowns, multi-year comparisons, and causal analysis of ESG score trends over time.

---

## Files 
- `ESG_Stock_Analysis.ipynb` – Full code and analysis
- `esg_data.csv` – ESG score dataset
- `stock_performance.csv` – Financial metrics generated from stock data
- `presentation.md` – Slide-style summary of this section
- `/images` – Visualizations used in the analysis

---

## Tools Used
- Python, Pandas, Matplotlib, yfinance
- Jupyter Notebook

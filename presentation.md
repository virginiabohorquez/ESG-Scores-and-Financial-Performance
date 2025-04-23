
# ESG and Stock Performance Presentation

---

## Virginia's Section

### Research Question
Do companies with higher ESG scores tend to have better stock performance (e.g., returns, volatility)?

---

### Data Sources
- `esg_data.csv`: ESG scores dataset including Environmental, Social, and Governance metrics.
- Yahoo Finance (via `yfinance` library): 1 year of daily historical stock prices for matching tickers.

---

### Methodology
1. Cleaned ESG dataset: selected relevant columns, standardized tickers, handled missing values.
2. Downloaded daily stock prices using `yfinance` for each company.
3. Calculated:
   - Average monthly return
   - Monthly volatility (standard deviation of returns)
4. Merged ESG and performance data using tickers.
5. Created correlation matrix and scatter plots to analyze patterns.

---

### Results

#### 🔹 Correlation Heatmap
Shows relationships between ESG scores and financial metrics (return & volatility).

#### 🔹 Scatter Plots
- **Total ESG Score vs. Monthly Return**
- **Total ESG Score vs. Volatility**
- **Environmental/Social Scores vs. Return**

Each chart helps visualize whether higher ESG scores are associated with better stock performance.

---

### Key Findings
- No strong correlation between ESG scores and average monthly returns.
- A slight negative correlation between ESG scores and volatility, suggesting more stability in ESG-conscious companies.

---

### Discussion
- **Limitations**:
  - Only 1 year of stock data; short-term trends
  - Volatility and return are limited proxies for long-term performance
- **Assumptions**:
  - ESG scores are accurate and comparable across companies
- **Future Work**:
  - Analyze across longer time periods
  - Break results down by industry
  - Explore causality between ESG score changes and price trends

---


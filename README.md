# ACC102 Financial Analysis Project (Local Simulation Version)

This project performs a comparative financial analysis of three major technology companies (AAPL, MSFT, GOOGL) using simulated quarterly financial data from 2019 to 2024.

---

## Project Overview
- **Objective**: Calculate key financial ratios and visualize trends to compare the profitability and financial health of three companies.
- **Data Source**: Local simulated financial data (generated using Python `pandas` and `numpy`).
- **Time Range**: 2019 Q1 to 2024 Q4.
- **Key Metrics**: ROA (Return on Assets), ROE (Return on Equity), Debt-to-Asset Ratio, and EPS (Earnings Per Share).

---

## Files Included
| File Name | Description |
|---|---|
| `acc102_financial_analysis.ipynb` | Main Jupyter Notebook containing all code and analysis |
| `roa_trend.png` | Line chart comparing ROA trends of the three companies |
| `README.md` | This project documentation |

---

## Key Steps in the Analysis
1. **Data Generation**: Created simulated quarterly financial data (Total Assets, Liabilities, Revenue, Net Income) for AAPL, MSFT, and GOOGL.
2. **Data Cleaning**: Handled missing values and ensured data consistency.
3. **Ratio Calculation**:
   - **Debt-to-Asset Ratio**: Measures financial leverage (`Total Liabilities / Total Assets`).
   - **ROA**: Measures asset profitability (`Net Income / Total Assets`).
   - **ROE**: Measures shareholder return (`Net Income / Shareholder Equity`).
   - **EPS**: Measures per-share profitability (`Net Income / Shares Outstanding`).
4. **Report Generation**: Created a bilingual financial health report for each company.
5. **Visualization**: Plotted a ROA trend chart to compare profitability over time.

---

## Sample Output
- The ROA trend chart shows that **MSFT** consistently maintained the highest ROA, indicating strong asset efficiency.
- **AAPL** has the lowest debt-to-asset ratio, reflecting a more conservative financial structure.
- All three companies show stable profitability trends over the 6-year period.

---

## How to Run the Code
1. Open the Jupyter Notebook `acc102_financial_analysis.ipynb`.
2. Run all cells in order.
3. The program will generate the analysis report and save the ROA trend chart as `roa_trend.png`.

---

## Environment
- Python 3.9+
- Required Libraries: `pandas`, `numpy`, `matplotlib`
- macOS compatible (uses `MacOSX` backend for stable plotting)
# Financial Data Analysis Project

## Overview
This project focuses on analyzing financial data from multiple stock indices using SQL, Python, and Power BI. Through this project, I enhanced my skills in:
- Writing advanced SQL queries for data manipulation and calculations.
- Utilizing Python for data analysis and automation.
- Creating insightful Power BI dashboards to visualize key metrics.

---

## Data Sources
### Indices Used
The following stock indices were analyzed:
- **BVSP (Ibovespa)**: Represents the performance of the Brazilian stock market, offering insights into emerging market trends.
- **DJI (Dow Jones Industrial Average)**: Tracks 30 large-cap U.S. companies, serving as a barometer for the U.S. economy.
- **FTSE (Financial Times Stock Exchange 100 Index)**: Highlights the performance of the top 100 companies listed on the London Stock Exchange.
- **GDAXI (DAX Index)**: Represents the top 40 companies on the Frankfurt Stock Exchange, reflecting the health of the German economy.
- **HSI (Hang Seng Index)**: Tracks major companies in Hong Kong, providing a snapshot of the Asian financial market.
- **NDX (NASDAQ-100 Index)**: Focuses on 100 of the largest non-financial companies listed on NASDAQ, emphasizing the technology sector.
- **RUT (Russell 2000 Index)**: Measures the performance of 2,000 small-cap U.S. companies, often used as an indicator of domestic market trends.
- **SPX (S&P 500 Index)**: Tracks the top 500 publicly traded U.S. companies, widely regarded as a representation of the overall market.

### Why These Indices?
These indices were chosen for their diverse representation of global markets and sectors, enabling a comprehensive analysis of market trends and investor behavior.

---

## Key Features
1. **SQL Analysis**:
   - Used **LEFT JOIN** to combine the primary dataset (`combined_data1`) with metadata (`ticker_metadata1`), enriching the data with ticker descriptions, currencies, and conversion rates.
2. **Metrics Calculated**:
   - **Price Change**: Percentage change in `Close` price compared to the previous month.
   - **Volume Change**: Percentage change in `Volume` compared to the previous month.
   - **Monthly Return**: Logarithmic return based on `Close` prices.
   - **Close in USD**: Converted `Close` price using currency conversion rates.
3. **Final Excel File**:
   The output file (`query_result.xlsx`) contains the following columns:
   - `Date`: Date of the record.
   - `Ticker`: Stock index ticker.
   - `Description`: Full name of the stock index.
   - `Currency`: Original currency of the index.
   - `ConversionToUSD`: Exchange rate used for USD conversion.
   - `AdjustedClose`: Adjusted closing price.
   - `Close`: Closing price in original currency.
   - `Close_in_USD`: Converted closing price in USD.
   - `Volume`: Trade volume.
   - `PriceChange`: Percentage change in closing price compared to the previous month.
   - `VolumeChange`: Percentage change in volume compared to the previous month.
   - `MonthlyReturn`: Logarithmic return of the closing price.
### Conversion Ratio
The conversion ratio for each currency to USD was calculated using today's exchange rates to ensure consistency and relevance. This enables seamless comparison of indices across different currencies.

---

## Applications of the Report
This report is designed to provide actionable insights for financial analysts, investors, and decision-makers. Potential use cases include:
- **Trend Analysis**: Identifying patterns in stock index performance over time.
- **Comparative Insights**: Comparing indices across currencies with unified USD metrics.
- **Risk Assessment**: Monitoring price and volume fluctuations for market stability.
- **Investment Strategy**: Supporting data-driven decisions for portfolio adjustments.

By integrating metrics like price changes, volume variations, and returns, the report enables stakeholders to make informed decisions based on historical and calculated trends.

---

## Project Highlights
- Developed advanced SQL queries to calculate metrics like price change, volume change, and monthly returns.
- Automated data handling and processing using Python.
- Designed a dynamic Power BI dashboard to visualize trends and insights, improving data-driven decision-making.

---

## Output
The final processed data includes:
- `Date`
- `Ticker`
- `Close_in_USD`
- `PriceChange`
- `VolumeChange`
- `MonthlyReturn`

The results are saved in an Excel file (`query_result.xlsx`) and visualized in Power BI dashboards.

---

## Tools and Technologies
- **SQL**: For data manipulation and complex calculations.
- **SQLite**: Managing combined and metadata tables.
- **Python**: For automating SQL execution and data exports.
- **Power BI**: For creating interactive visualizations and dashboards.

---

## Skills Developed
This project significantly improved my:
- SQL proficiency: Writing efficient and complex queries.
- Python expertise: Automating data workflows and integrating SQL results.
- Power BI skills: Designing impactful dashboards to communicate insights effectively.

---

## Author
Ella Batdelger
batdelgm@dickinson.edu

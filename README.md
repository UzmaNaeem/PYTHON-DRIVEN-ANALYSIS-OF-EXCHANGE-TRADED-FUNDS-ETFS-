# Python-Driven Analysis of Exchange-Traded Funds

## Summary

This project presents an in-depth analysis of Exchange-Traded Funds (ETFs) using Python. The analysis covers various aspects of ETFs, including performance metrics, risk factors, and compliance, aiming to provide insights into selecting optimal ETFs based on investment strategies. The dataset, sourced from Kaggle, includes 129 columns and 2,264 rows, offering a comprehensive view of ETFs' characteristics.

## Explanation of Data

**Dataset Overview:**
- **Name:** Exchange-Traded Funds (ETFs) and Mutual Funds Composition & Yield Metrics
- **Source:** Kaggle
- **Columns:** 129
- **Rows:** 2,264

**Key Columns:**
- `inceptionDate`: Fund's inception date
- `quoteDate`: Date of quote
- `ter`: Total Expense Ratio
- `quote`: Quote Price
- `fundSizeMillions`: Size of the fund in millions
- `isin`: International Securities Identification Number
- `ytdReturnCUR`: Year-to-Date Return in Currency
- `yearVolatilityCUR`: Year Volatility in Currency
- `currencyRisk`: Currency risk (hedged/unhedged)
- `UCITSCompliance`: Compliance with UCITs regulations
- `domicileCountry`: Country of domicile
- `fundCurrency`: Currency of the fund

**Objective:**
- To identify top-performing ETFs.
- To understand the effect of domicile countries, volatility, and currency risks on ETF performance.
- To provide actionable insights based on ETF characteristics and investor strategies.

## Results / Key Findings

### 1. Relationship Between Volatility and Return

**Scatter Plot:**
![Scatter Plot](path/to/scatter-plot.png)
- **Description:** The scatter plot illustrates the relationship between Yearly Volatility and Year-to-Date Returns, color-coded by Risk Groups. This visual helps in understanding how volatility impacts returns across different risk profiles.

**Box Plot:**
![Box Plot](path/to/box-plot.png)
- **Description:** The box plot shows the distribution of returns within each Risk Group, highlighting central tendencies, variability, and potential outliers.

### 2. Top 5 ETFs with the Best Returns

**Top ETFs Plot:**
![Top ETFs](path/to/top-etfs.png)
- **Description:** This figure represents the top 5 ETFs with the highest returns, emphasizing attractive investment opportunities for future investors.

### 3. Concentration of ETFs per Domicile Country

**Domicile Country Distribution:**
![Domicile Countries](path/to/domicile-countries.png)
- **Description:** The graph shows the distribution of ETFs across different domicile countries. Ireland, Luxembourg, Germany, and France are prominent, highlighting the geographic spread of ETFs.

### 4. Concentration of ETFs per Currency

**Currency Distribution:**
![Currency Distribution](path/to/currency-distribution.png)
- **Description:** This figure illustrates the distribution of ETF currencies. USD is the most frequent, indicating a significant concentration of ETFs in US dollars.

### 5. Best ETFs Based on Criteria

**Best ETFs by Risk Group:**
![Best ETFs](path/to/best-etfs.png)
- **Description:** The visualization shows the distribution by risk group of the top 30 ETFs meeting various criteria. Notably, 20 out of 30 best ETFs are categorized as having a moderate risk level.

## Conclusion

**Benefits:**
- Provides valuable insights into ETF performance and selection.
- Identifies top-performing ETFs and highlights diversification opportunities.
- Offers a nuanced understanding of risk-return dynamics.

**Challenges:**
- Data granularity limitations.
- Complex market dynamics and model improvement opportunities.
- Impact of external economic factors.

**Learnings:**
- Emphasized the importance of data cleaning for ensuring accuracy and reliability.
- Highlighted the role of clean data in facilitating meaningful analysis and decision-making.

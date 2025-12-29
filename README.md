# Impact of Global Commodity Prices on Macroeconomic Indicators  
### An Econometric Analysis of India and the USA (2010–2023)

## 📌 Project Overview
This project examines how global commodity price movements—specifically oil, gold, and silver—impact key macroeconomic indicators in India and the United States. Using econometric techniques, the study compares how a developing, commodity-import-dependent economy (India) responds to price shocks versus a developed, more diversified economy (USA).

The analysis combines exploratory data analysis, multiple linear regression, and time-series modeling to uncover structural differences in macroeconomic sensitivity across countries.

---

## 🎯 Objectives
- Analyze the effect of commodity prices on:
  - Inflation
  - GDP Growth
  - Unemployment
  - Interest Rates
- Compare commodity price pass-through effects between India and the USA
- Test econometric hypotheses related to cost-push inflation and energy dependence
- Evaluate model performance and generalization across countries

---

## 📊 Data Sources
- **Global Macroeconomic Indicators (2010–2023)**  
  GDP growth, inflation, unemployment, interest rates, stock indices  
  Source: Kaggle – Global Economic Indicators Dataset  

- **Commodity Prices (World Bank Pink Sheet)**  
  Crude oil, gold, silver, energy, agriculture, and metals indices  
  Source: World Bank Commodity Markets Outlook  

Macroeconomic data was aligned to monthly frequency using interpolation to match commodity price data.

---

## 🧠 Methodology
- Exploratory Data Analysis (EDA)
  - Trend analysis
  - Scatter plots
  - Correlation heatmaps
- Econometric Modeling
  - Multiple Linear Regression (OLS)
  - Model diagnostics (R², MSE, residual analysis)
- Time-Series Modeling
  - Stationarity testing (ADF)
  - ARIMA modeling (where applicable)
- Comparative country-level analysis

---

## 📈 Key Insights
- India shows strong sensitivity to global energy prices, especially for inflation and interest rates.
- Commodity prices explain up to **50–60%** of variation in some Indian macro indicators.
- The USA exhibits weaker and less consistent relationships due to economic diversification.
- Gold does not consistently act as a safe-haven asset against stock market movements in either country.
- GDP growth is weakly predicted by commodity prices in both economies.

---

## 🧪 Tools & Technologies
- Python
- Pandas, NumPy
- Statsmodels
- Matplotlib, Seaborn
- Scikit-learn

---

## 📂 Repository Structure

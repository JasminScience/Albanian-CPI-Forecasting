# Albanian-CPI-Forecasting

# Comparative Forecasting Performance of SARIMA, ETS, and NNAR Models for the Consumer Price Index of Fruits and Vegetables in Albania

🏆 **International Conference Publication & Presentation**  
*This pioneering macroeconomic research paper was officially accepted, published, and presented orally at an International Conference (ICABEH 2026).*

## 📌 Project Overview
This study represents a pioneering research initiative—**the first of its kind in Albania**—focused on analyzing and forecasting the Consumer Price Index (CPI) specifically for the highly volatile fresh produce sector (Fruits & Vegetables). 

By evaluating traditional statistical frameworks against machine learning techniques, this paper provides critical data-driven models essential for monetary policy, financial institutions (inflation monitoring), and retail supply chain management in Albania.

## 📄 Read the Full Research Paper
The complete peer-reviewed paper containing the full methodology, state-space formulations, and residual diagnostics is available in this repository.

👉 **[Click Here to Open/Download the Full PDF Paper](./research_paper.pdf)**

## 📊 Key Methodology & Statistical Insights
- **Data Source:** Monthly CPI dataset from the Albanian Institute of Statistics (INSTAT), spanning from January 2007 to December 2025 (2,508 observations).
- **Models Implemented:** Seasonal ARIMA (SARIMA), Error-Trend-Seasonal (ETS), and Neural Network Autoregression (NNAR).
- **Model Evaluation Metrics:** Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and First-Order Autocorrelation (ACF1).

### 📈 Core Findings:
- **Top Performer:** The **SARIMA model achieved superior forecasting accuracy** for both food sub-indices, effectively eliminating residual autocorrelation.
  - **Fruit CPI Model:** `SARIMA(1,0,0)(0,1,2)[12] with drift` reached an exceptional **MAPE of 2.38%** (ACF1 = 0.021).
  - **Vegetable CPI Model:** `SARIMA(2,1,1)(0,1,1)[12]` achieved a **MAPE of 3.76%** (ACF1 = -0.018).
- **Market Volatility:** The analysis mathematically demonstrated that the vegetable market carries higher seasonal volatility (point forecasts peaking in March at 178.38) compared to fruits (peaking in June at 143.04), requiring wider confidence intervals due to supply-side constraints.

## 🛠️ Software & Tools Used
- **Language:** R (tidyr, tseries, forecast, ggplot2)
- **Stationarity Testing:** Augmented Dickey-Fuller (ADF) & KPSS tests.

## 👤 Author Information
- **Jasmina Duka** - Faculty of Natural and Human Sciences, Fan S. Noli University, Korçë, Albania.
- **ORCID:** [0009-0003-6471-693X](https://orcid.org)
- **Contact:** jasminaduka02@gmail.com

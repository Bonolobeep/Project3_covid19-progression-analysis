# Project3_covid19-progression-analysis
Time series analysis and ARIMA forecasting of global COVID-19 case progression using Johns Hopkins University data.

**Python Time Series Analysis of COVID-19 Global Progression**

**What is this?**
A data science project analyzing and forecasting the global spread of COVID-19 using Johns Hopkins University data. The project identifies the nature of the pandemic, compares regional trends, and uses an ARIMA model to forecast case progression.

**Who made this?**
Bonolo Ramolapong

Completed 22 March 2026

**Tools Used**
Pandas, Matplotlib, Statsmodels (ARIMA, Dickey-Fuller, ACF/PACF)

**How to Run**
1. Install: pip install pandas matplotlib statsmodels
2. Run the provided Jupyter Notebook
3. Data loads automatically from the Johns Hopkins GitHub repository — no file download needed

**Key Findings**
- The US had the highest case and death counts, exceeding 100 million cases and 1.1 million deaths
- Each region had a distinct wave — India peaked during Delta (mid-2021), Brazil in early 2021, Russia in late 2021
- The Dickey-Fuller test confirmed the data was non-stationary, justifying the use of ARIMA with d=1
- ACF and PACF plots confirmed ARIMA(1,1,1) as the appropriate model
- The model achieved a remarkably low MAPE of 0.02%, confirming reliable short-term forecasting

**Files**
- covid_analysis.ipynb — full analysis and forecasting notebook
- README.md — this file

**Data Source**
Johns Hopkins University COVID-19 Repository — https://github.com/CSSEGISandData/COVID-19

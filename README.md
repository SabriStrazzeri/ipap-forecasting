# 📈 IPAP Time Series Analysis & Forecasting

## 📌 Objective
Analyze and forecast the Tourist Apartment Price Index (IPAP) in Spain from 2003 to 2022 using time series modeling techniques.

## 📂 Dataset
The dataset `IPAP.xlsx` contains monthly IPAP values over a 20-year period. It must be placed in the root directory to run the analysis.

## 🛠️ Tools Used
`Python`, `Pandas`, `Matplotlib`, `Seaborn`, `Statsmodels`, `pmdarima`, `OpenPyXL`

## 🧪 Approach
1. **Data Preprocessing**:
   - Cleaned and formatted the date column.
   - Handled missing values and set the time index.

2. **📊 Visualization**:
   - Plotted the IPAP time series.
   - Created seasonal plots to observe yearly patterns.

3. **🎯 Seasonal Decomposition**:
   - Applied additive decomposition to extract trend, seasonality, and residuals.
   - Visualized seasonal coefficients and adjusted series.

4. **✂️ Train-Test Split**:
   - Split the data into training (first 240 months) and testing (last 12 months).

5. **🧪 Smoothing Models**:
   - Applied Simple Exponential Smoothing, Holt’s Linear Trend, Damped Trend, and Holt-Winters models.
   - Compared forecasts and visualized model components.

6. **🔁 ARIMA Model**:
   - Performed differencing and analyzed ACF/PACF plots.
   - Built a manual ARIMA model and evaluated its performance.

7. **📆 Seasonal ARIMA Model**:
   - Applied seasonal differencing and built a SARIMA model.
   - Used `pmdarima` for automatic model selection and forecasting.

## 📈 Results
- Seasonal decomposition revealed strong summer peaks in IPAP values.
- Holt-Winters and SARIMA models captured both trend and seasonality effectively.
- Forecasts aligned well with actual test data, validating the models.

## 🤓 What I Learned
- Time series decomposition is essential for understanding underlying patterns.
- Smoothing models provide interpretable forecasts and are useful for short-term predictions.
- ARIMA and SARIMA models are powerful tools for capturing complex temporal dynamics.
- Visual diagnostics and error metrics (MSE, MAE) are crucial for model evaluation.

## 📁 Repo Contents
- `notebooks/` – IPAP forecasting notebook.
- `data/` – IPAP dataset.


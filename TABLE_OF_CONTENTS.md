 TABLE OF CONTENTS

——— ExploratoryDataAnalysis ———
- Imports and Defines
- Data Inspection
- Data Visualization
- Data Analysis
- Hypothesis Test

——— ARIMA & SARIMA ——— 
- Imports and Defines
  - Imports
  - Define Functions
  - Define Univariate Time-Series
- Stationarity of the Time-Series
  - Data transformation and its graphical representation
  - Normality tests
    - Jarques-Bera
    - Kolmogorov-Smirnov
  - Unit Root and Stationarity Tests
    - The Augmented Dickey-Fuller test
    - Kwiatkowski-Phillips-Schmidt-Shin
  - Correlation plots
- (S)ARIMA Selection
  - Pre-processing
  - Model training
  - Model Comparison based on Information Criteria
  - Selected Models Information Criteria Comparison
  - Selected Models Cross-Validation
- Model Validation
  - Model Residual Analysis
  - Normality tests
     - Kurtosis and Kurtosis Test
     - Skew and Skewness Test
     - Jarque-Bera and Kolmogorov-Smirnov tests
  - Engle's Test for Autoregressive Conditional Heteroscedasticity (ARCH)
  - Test for No Autocorrelation
     - Brock–Dechert–Scheinkman test
     - Breusch-Godfrey test [NOT IN SARIMA]
     - Box-Pierce and Ljung-Box tests
     - QQplot
     - Auto-correlation and Partial Auto-correlation functions
- Model Prediction
  - Model Prediction Overview


——— ExponenTialSmoothing ———
- Imports and Defines
  - Imports
  - Define Functions
  - Define Univariate Time-Series
- Data Visualization
- Model Training
  - Single Exponential Smoothing
    - TS (N, N) - Simple Exponential Smoothing
  - Double Exponential Smoothing
    - TS (A, N) - Holt’s linear method
    - TS (Ad, N) - Additive damped trend method
  - Triple Exponential Smoothing
    - TS (N, A) method
    - TS (A, A) - Additive Holt-Winters method
    - TS (Ad, A) method
    - TS (N, M) method
    - TS (A, M) Multiplicative Holt-Winters’ method
    - TS (Ad, M) Holt-Winters’ damped method
- Model Selection
- Model Validation
  - Normality Test
    - Kurtosis and Kurtosis Test
    - Skew and Skewness Test
    - Jarque-Bera test
    - Kolmogorov-Smirnov test
  - Engle's Test for Autoregressive Conditional Heteroscedasticity (ARCH)
  - Test for No Autocorrelation
    - Brock–Dechert–Scheinkman test
    - Box-Pierce and Ljung-Box tests
    - QQplot
    - Plot Auto-correlation and Partial Auto-correlation functions
- Model Prediction
  - Model Prediction Overview
  
——— DeepNeuralNetwork (& DNN_ourApproach) ———
- Imports and Defines
  - Imports
  - Define Functions
  - Define Univariate Time-Series
- Training Deep Neural Network
  - Data Pre-Processing
  - Visualization of Data Pre-Processed
  - Model Selection (tune hyper-parameters)
  - Cross-Validation
    - Compute Cross-Validation Errors
    - Cross-Validation Performance
    - Cross-Validation Plot
- Model forecasting
  - Perform statistics on predictions
  - Statistics cleaning
  - Plot Prediction
  - Plot Forecast in-sample vs out-sample

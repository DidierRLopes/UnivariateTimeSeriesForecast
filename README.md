# Univariate Time Series Forecast

This study was developed with Filipe Roberto Ramos (https://ciencia.iscte-iul.pt/authors/filipe-roberto-de-jesus-ramos/cv) for his phD thesis entitled "Data Science in the Modeling and Forecasting of Financial timeseries: from Classic methodologies to Deep Learning". Submitted in 2021 to Instituto Universitário de Lisboa - ISCTE Business School, Lisboa, Portugal.


<!-- TABLE OF CONTENTS -->

<ol>
  <li>
    <a href="#Notebooks">Notebooks</a>
    <ul>
      <li><a href="#ExploratoryDataAnalysis">ExploratoryDataAnalysis</a></li>
      <li><a href="#Arima-and-Sarima">ArimaAndSarima</a></li>
      <li><a href="#ExponenTialSmoothing">ExponenTialSmoothing</a></li>
      <li><a href="#DeepNeuralNetwork">DeepNeuralNetwork</a></li>
    </ul>
  </li>
  <li><a href="#Citation">Citation</a></li>
</ol>

This code was developed with co-autorship with Filipe Roberto de Jesus Ramos (https://ciencia.iscte-iul.pt/authors/filipe-roberto-de-jesus-ramos/cv) for his PhD thesis entitled: "Modeling and Forecasting of Time-Series: A data science approach that compares classic methodologies with deep learning methodologies"

The contents of this repository can be seen below:

## ExploratoryDataAnalysis
* Imports and Defines
* Data Inspection
* Data Visualization
* Data Analysis
* Hypothesis Test

## ARIMA and SARIMA 
* Imports and Defines
  * Imports
  * Define Functions
  * Define Univariate Time-Series
* Stationarity of the Time-Series
  * Data transformation and its graphical representation
  * Normality tests
   * Jarques-Bera
   * Kolmogorov-Smirnov
  * Unit Root and Stationarity Tests
   * The Augmented Dickey-Fuller test
   * Kwiatkowski-Phillips-Schmidt-Shin
  * Correlation plots
* (S)ARIMA Selection
  * Pre-processing
  * Model training
  * Model Comparison based on Information Criteria
  * Selected Models Information Criteria Comparison
  * Selected Models Cross-Validation
* Model Validation
  * Model Residual Analysis
  * Normality tests
   * Kurtosis and Kurtosis Test
   * Skew and Skewness Test
   * Jarque-Bera and Kolmogorov-Smirnov tests
  * Engle's Test for Autoregressive Conditional Heteroscedasticity (ARCH)
  * Test for No Autocorrelation
   * Brock–Dechert–Scheinkman test
   * Breusch-Godfrey test [NOT IN SARIMA]
   * Box-Pierce and Ljung-Box tests
   * QQplot
   * Auto-correlation and Partial Auto-correlation functions
* Model Prediction
  * Model Prediction Overview


## ExponenTialSmoothing
* Imports and Defines
  * Imports
  * Define Functions
  * Define Univariate Time-Series
* Data Visualization
* Model Training
  * Single Exponential Smoothing
   * TS (N, N) - Simple Exponential Smoothing
  * Double Exponential Smoothing
   * TS (A, N) - Holt’s linear method
   * TS (Ad, N) - Additive damped trend method
  * Triple Exponential Smoothing
   * TS (N, A) method
   * TS (A, A) - Additive Holt-Winters method
   * TS (Ad, A) method
   * TS (N, M) method
   * TS (A, M) Multiplicative Holt-Winters’ method
   * TS (Ad, M) Holt-Winters’ damped method
* Model Selection
* Model Validation
  * Normality Test
   * Kurtosis and Kurtosis Test
    * Skew and Skewness Test
    * Jarque-Bera test
    * Kolmogorov-Smirnov test
  * Engle's Test for Autoregressive Conditional Heteroscedasticity (ARCH)
  * Test for No Autocorrelation
   * Brock–Dechert–Scheinkman test
   * Box-Pierce and Ljung-Box tests
   * QQplot
   * Plot Auto-correlation and Partial Auto-correlation functions
* Model Prediction
  * Model Prediction Overview
  
  
## DeepNeuralNetwork
And **DNN_OurApproach**

* Imports and Defines
  * Imports
  * Define Functions
  * Define Univariate Time-Series
* Training Deep Neural Network
  * Data Pre-Processing
  * Visualization of Data Pre-Processed
  * Model Selection (tune hyper-parameters)
  * Cross-Validation
   * Compute Cross-Validation Errors
   * Cross-Validation Performance
   * Cross-Validation Plot
* Model forecasting
   * Perform statistics on predictions
   * Statistics cleaning
   * Plot Prediction
   * Plot Forecast in-sample vs out-sample


## Citation

APA 

`Ramos, F. (2021). Data Science na Modelação e Previsão de Séries Económico-financeiras: das Metodologias Clássicas ao Deep Learning. (PhD Thesis submitted, Instituto Universitário de Lisboa - ISCTE Business School, Lisboa, Portugal).`

```
@phdthesis{FRRamos2021,
      AUTHOR = {Filipe R. Ramos},
      TITLE = {Data Science na Modelação e Previsão de Séries Económico-financeiras: das Metodologias Clássicas ao Deep Learning},
      PUBLISHER = {PhD Thesis submitted, Instituto Universitário de Lisboa - ISCTE Business School, Lisboa, Portugal},
      YEAR =  {2021}
}
```

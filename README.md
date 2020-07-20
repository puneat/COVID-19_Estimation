# COVID-19 Disease Spread Estimation in India
Covid-19 Predictions Using a Novel Hybrid model of Log-Likelihood Maximized Autoregressive Integrated Moving Average (ARIMA) and minimization of residual error using Long Short-Term Memory Networks (LSTM) The data for our purpose shall be obtained from multiple sources such as, COVID19-India API and John Hopkins University.

The model has the aim of implementing the following:
<li>Build an ML model for predicting the number of total infections in India till 31st of July 2020.</li>
<li>Build an ML model for predicting the number of deaths in India till 31st of July 2020.</li>
<li>Build an ML model and predict recovery rate and death rate in India for the period 15th June to 31st of July.</li>

<p>COVID-2019 disease has been recognized as a global threat, and several studies are being conducted using various mathematical models,using machine learning methods and statistical methods to predict the probable progression of this epidemic. Therefore choosing the correct method is vital for an accurate estimation.</p>

<p>
  <b>Methodology</b> 
The data is divided into its constituent components, namely, Confirmed Cases, Recovered Cases, and Deaths. Since the data has an increased trend, stationarity is enforced and the data is fit to a ARIMA model, after its AR , Lag terms and MA terms have been found using various techniques such as - Auto-correlation, Partial-autocorrelation, Augmented Dicky Fuller test, Akaike Information Criterion test, P-value test, Residual Analysis, Grid Search.<br>
Based on the selected values of AR and MA, a ARIMA model is created and data is fit. This ARIMA model is then used to make the predictions for the future. The predictions made by ARIMA are then fed into a pre-trained LSTM Network for removal of any non-linear residual error and white noise. The denoised output from the LSTM is the final prediction.
To cross-validate our proposed model, S-I-R modelling and Polynomial Fitting shall also be performed to set a benchmark and compare the performance. <br>
The methodology for this project is divided into nine parts, namely,
<li>Exploratory data analysis (EDA)</li>
<li>Confirmatory data analysis (CDA) with SEIR Modelling Inferences</li>
<li>Polynomial Fitting Benchmark</li>
<li>Data Pre-Processing</li>
<li>Statistical analysis of the underlying variables</li>
<li>Model building and training</li>
<li>End Result</li>
  </p>


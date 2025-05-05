## 1. TimeSeries Analysis - AR3 Model Parameter Estimation Using Yule-Walker Equations
### Key Features
Simulates an AR(3) process where the current value depends on the last three values and random noise.
Estimates AR coefficients and variance using Yule-Walker equations.
Visualizes the simulated process, autocorrelation (ACF), and partial autocorrelation (PACF).
### How to Use
Open the notebook in an R environment.
Run the code to simulate the AR(3) process and estimate parameters.
View the plots and results.
### Outputs
Estimated AR coefficients and variance.
Plots of the simulated process, ACF, and PACF.
### Requirements
R programming language with the stats library.
### Notes
Assumes the AR process is stationary.
Uses a large sample size for accuracy.
### License
Licensed under the MIT License.

## 2. Timeseries Modeling Simulation
### Key Features
Covers typical timeseries modeling steps, including trend checks, transformations, and model order identification.
Simulates ARIMA processes and evaluates models using AIC, SSE, and residual autocorrelation tests.
Visualizes simulated processes and model diagnostics.
### How to Use
Open the notebook in an R environment.
Run the code to simulate ARIMA processes and evaluate models.
Compare models and view diagnostic plots.
### Outputs
Simulated ARIMA processes.
Model evaluation metrics (AIC, SSE).
Diagnostic plots for residuals and fitted models.
### Requirements
R programming language with the forecast and astsa libraries.
### Notes
Includes Ljung-Box Q statistic to check residual autocorrelation.
Demonstrates model selection based on AIC and SSE.
### License
Licensed under the MIT License.

## 3. Modeling Recruitment Time Series as an AR Process
### Key Features
Models recruitment data from the astsa package as an AR process.
Estimates AR coefficients using Yule-Walker equations.
Visualizes recruitment data, ACF, and PACF.
### How to Use
Open the notebook in an R environment.
Run the code to analyze recruitment data and estimate AR coefficients.
View the plots and results.
### Outputs
Estimated AR coefficients and variance.
Plots of recruitment data, ACF, and PACF.
### Requirements
R programming language with the astsa library.
### Notes
Subtracts the mean to center the data before analysis.
Assumes the recruitment data is stationary.
### License
Licensed under the MIT License.

## 4. Practical Timeseries - Basics
### Key Features
Simulates basic distributions (normal, uniform, Poisson, coin flips) and calculates their sample statistics.
Demonstrates AR(1) and AR(2) process simulations and stationarity checks.
Visualizes ACF and PACF for AR processes.
### How to Use
Open the notebook in an R environment.
Run the code to simulate distributions and AR processes.
View the plots and analyze the results.
### Outputs
Simulated distributions and AR processes.
ACF and PACF plots for AR(1) and AR(2) processes.
### Requirements
R programming language.
### Notes
Explains the relationship between stationarity and AR process parameters.
Includes examples of negative correlations in AR processes.
### License
Licensed under the MIT License.


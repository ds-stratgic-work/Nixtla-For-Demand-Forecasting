# Understanding-Nixtla-For-Forecasting

## The purpose :
StatsForecast provides a variety of popular univariate time series forecasting models, such as automatic ARIMA, ETS, CES, and Theta modeling, all optimized for superior performance through the use of numba. Additionally, it offers a comprehensive set of benchmarking models.

## Installation
!pip install statsforecast

## Example and Minimul Usage
Utilizing the statsforecast library, 
- import the StatsForecast class along with the AutoARIMA model,
-  and AirPassengersDF utility.
-  Create a DataFrame object named df using AirPassengersDF.
-  Instantiate a StatsForecast object named sf with an AutoARIMA model configured for a season length of 12, and a
-  Frequency of 'M'.
-  Fitting the model to the DataFrame,
-  Proceed to make predictions for the next 12 time steps with a confidence level of 95%.

## Technology
 Python


### References:
https://pub.towardsai.net/introduction-to-nixtla-for-demand-forecasting-2b97ab5e0854
https://nixtlaverse.nixtla.io/statsforecast/docs/tutorials/statisticalneuralmethods.html
https://github.com/robjhyndman/M4metalearning/blob/master/docs/M4_methodology.html#features
https://nixtlaverse.nixtla.io/mlforecast/index.html


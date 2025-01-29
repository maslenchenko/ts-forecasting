# Time Series Forecasting

### Author
Maslenchenko Oleksandra

### Aim
The aim of this mini-project is to explore different approaches to forecasting time-series data, starting with the most widely used methods, such as ARIMA models, and extending to more unconventional techniques, such as applying CNNs. This project is both exploratory and experimental in nature.  

###  Overview
This project consists of two parts:

**Part 1: Data Preparation, EDA and Exploring Classical Statistical Approaches** <br>
This section covers data preprocessing steps, cleaning, and transformations necessary for time series analysis, including stationarity checks, ACF/PACF analysis, and decomposition techniques. The models explored in this part include:

- Moving Average (MA) Smoothing
- Single, Double, and Triple Exponential Smoothing
- Autoregressive (AR) Models
- Moving Average (MA) Models
- Autoregressive Moving Average (ARMA)
- Autoregressive Integrated Moving Average (ARIMA)
The results are as follows:
<table>
  <tr>
    <th>Model</th>
    <th>Data</th>
    <th>MAPE</th>
  </tr>
  <tr>
    <td>MAS</td>
    <td>Multiplicative</td>
    <td>6.85%</td>
  </tr>
  <tr>
    <td>SES</td>
    <td>Additive</td>
    <td>6.38%</td>
  </tr>
  <tr>
    <td>DES</td>
    <td>Multiplicative</td>
    <td>17.72%</td>
  </tr>
  <tr>
    <td>TES</td>
    <td>Additive</td>
    <td>18.19%</td>
  </tr>
  <tr>
    <td>AR</td>
    <td>Multiplicative</td>
    <td>6.15%</td>
  </tr>
  <tr>
    <td>MA</td>
    <td>Multiplicative</td>
    <td>5.95%</td>
  </tr>
  <tr>
    <td>ARMA</td>
    <td>Multiplicative</td>
    <td>5.98%</td>
  </tr>
  <tr>
    <td>ARIMA</td>
    <td>Multiplicative</td>
    <td>12.97%</td>
  </tr>
</table>



**Part 2: Incorporating Exogenous Factors and Exploring Advanced Models** <br>
This section focuses on integrating exogenous factors into time-series forecasting and experimenting with various regression-based machine learning models, deep learning approaches, and a state-of-the-art (SOTA) model. <br>

The models explored in this part include:

- SARIMA(X) (Seasonal ARIMA with exogenous variables)
- Support Vector Regression (SVR)
- Random Forest
- XGBoost
- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)
- CNN (Convolutional Neural Networks)
- Facebook Prophet (SOTA time-series forecasting model)
- ARIMA with Fourier terms (for handling seasonality)
The results are as follows:

<table>
  <tr>
    <th>Model</th>
    <th>MAPE</th>
  </tr>
  <tr>
    <td>SARIMA</td>
    <td>11.698%</td>
  </tr>
   <tr>
    <td>SARIMAx</td>
    <td>12.714%</td>
  </tr>
   <tr>
    <td>SVR</td>
    <td>16.635%</td>
  </tr>
   <tr>
    <td>RF</td>
    <td>23.477%</td>
  </tr>
   <tr>
    <td>XGBoost</td>
    <td>20.809%</td>
  </tr>
  <tr>
    <td>FB Prophet</td>
    <td>10.278%</td>
  </tr>
  <tr>
    <td>LSTM</td>
    <td>21.261%</td>
  </tr>
  <tr>
    <td>GRU</td>
    <td>16.356%</td>
  </tr>
  <tr>
    <td>CNN</td>
    <td>28.172%</td>
  </tr>
  <tr>
    <td>ARIMA with Fourier</td>
    <td>14.646%</td>
  </tr>
</table>


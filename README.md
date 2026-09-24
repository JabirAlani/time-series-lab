# Time series lab

An interactive, in-browser companion to Session 5 of the L7 Time Series course: AR models and exponential smoothing.

**Live app:** [https://YOUR-USERNAME.github.io/time-series-lab/](https://jabiralani.github.io/time-series-lab/)

## What's inside

1. **Process simulator** – simulate AR, MA, ARMA, ARIMA and SARIMA processes. See the roots on the unit circle (stationarity and invertibility) and the ACF/PACF patterns.
2. **AR to SARIMAX** – fit AR, MA, ARMA, ARMAX, ARIMA, ARIMAX, SARIMA and SARIMAX models, search orders by AIC, and get the matching statsmodels code.
3. **Exponential smoothing** – all 30 ETS models (error × trend × season), including SES, Holt, damped Holt and Holt-Winters, with automatic fitting and AIC selection.
4. **Compare models** – rank every model against naive baselines on a hold-out or with rolling-origin evaluation.

The data is simulated in the browser, or you can paste your own series. Nothing is uploaded anywhere.

## Run it locally

Open `index.html` in any modern browser. It needs an internet connection to load Chart.js and the fonts from their CDNs.

## Notes

Models are fitted in JavaScript (conditional least squares for the ARIMA family, SSE or maximum likelihood for ETS), so results are close to, but not identical to, statsmodels.

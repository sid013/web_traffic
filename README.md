
Mitigating Cold Start via web traffic prediction
- Identified a shortcoming of AWS Lambda, Cold Start(Significantly higher response time if there is gap between function calls)
- Since backend function call is correlated to site traffic, built a web traffic forecasting model
- Used WikiPedia Web Traffic, built baseline for prediction accuracy using FB Prophet and ARIMA.
- Developed a hybrid CNN-LSTM attention model achieving 57% improvement in baseline.
-  Halved the Lambda response time by implementing model-driven pre-warming, improving user experience.



Predicting web-traffic using multi-step time-series forecasting
For dataset https://www.kaggle.com/c/web-traffic-time-series-forecasting/data
Report contains the result of various time-series forecasting techniques.
Report_2 contains the result of validation of the solution approach on actual AWS Lambda deployement

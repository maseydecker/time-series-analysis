# Time Series Analysis
A time series of daily revenue from a telecommunications company has been provided with the last 2 years of revenue

## Research Question

Using this data provided, what are some meaningful patterns within and what is the predicted forecast of revenue for the next 6 months? The data will be prepared and analyzed to find identifiable patterns with the revenue of the company over the 2 years of operations. We will perform a time series analysis using an ARIMA model to make predictions on the forecasted revenue based on the historical data gathered.

## Data Summary and Implications

I created and fitted an ARIMA model using auto ARIMA and SARIMAX. The auto ARIMA gave us the model with the best AIC of 985. I also found the Mean Absolute Error of the model. As the output is 0.428 and is close to 0, we can conclude that error rates of the analysis are low considering how many observations are in the data. Based on our analysis, we can see that the revenue of the company is linearly increasing over time and will continue to grow. There is some seasonality to the revenue, but overall, an upwards trend. We can expect the company to continue to have growth. The biggest dips in the upward trend is between July to October in both years. I would recommend determining if these dips in the revenue had anything to do with the churn of the customers and make a plan accordingly.

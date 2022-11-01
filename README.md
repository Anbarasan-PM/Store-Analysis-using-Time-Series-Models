# Store Sales - Time Series Forecasting
Using the appropriate Time Series Model for forecasting the sales of the store
 1) required libraries :
                      pandas,seaborn,matplot,statsmodels
 
 2) Concepts used :
           -> Naive Forecasting : However it takes previous absolute value as present forecasting values it is not efficient in this case.
           
           -> Simple Average    : It tells how average sales but the data follows some pattern it cannot be captured by this forecasting technique.
           
           -> Simple Moving Average :It is the better forecasting technique compared to the above. But still the accuracy is not efficient.
           
           -> Simple Exponential Smoothing : It can be used when there is no trend and seasonality.i-e) It acn be used when the data has only level.
                                              But the data has some pattern in it.
                                              
           -> Holt Exponential Smoothing : It gives high accuracy compared to Simple Exponential Smoothing but it captures only trends because of this it shows high 
                                           variability in result.
                                           
           -> Holt Winter Exponential Smoothing : It captures both trend and seasonality. And it gives high accuracy of result.
           
           -> ARIMA : It performs well in this case.However as far i understood Holt - Winter is the special case of ARIMA(Auto-Regressive Integrated Moving Average).
           
   3) Conclusion:
              Holt Winter Exponential Smoothing gives the best accurate result and it forecast good in this data.


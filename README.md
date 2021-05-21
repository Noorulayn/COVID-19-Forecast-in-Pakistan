# COVID-19-Forecast-in-Pakistan

 This is a time-series dataset and it is being updated on a daily basis. Refer to the following resources:
1. Novel Corona Virus 2019 Dataset for dataset description
2. Johns Hopkins Coronavirus Resource Center for graphical view of the data



Countries following the same trend as of Pakistan were found by diving their no. of cases of each day with the no. of days. These values were then subtracted from the Pakistan values and then difference was later on summed. The countries with minimum difference with pakistan showed similar results.

For modelling, the ARIMA was chosen as it shows the best result. In this function we returned the ‘predictions’ that stored all the forecasted values. The similar countries data was given to this model one by one and it predicted the values from 10th May to 27th June i.e 31 days into the future.

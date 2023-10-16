# DailyClimate_TimeSeriesAnalysis_NTI

## Dataset

I downloaded the 'Daily Climate Time-Series' dataset from Kaggle, preprocessed the data, and parsed the date column to a datetime type column. 

## ADFuller Test

Then I tried the ADFuller Test on the training data frame df1 and noticed that the p-value was larger than 0.05 so I tried square rooting the data. I did the ADFuller test again to find the p-value dropping to 0.02.

## ARIMA & SARIMAX models

### Mean temperature on Test data prediction - ARIMA
After visualizing the training and testing data, I then trained ARIMA & SARIMAX models on the training data. I tested the ARIMA model once on forecasting the test data time period and this is what I got:
!![image](https://github.com/YasmineElegily/DailyClimate_TimeSeriesAnalysis_NTI/assets/69461886/7f8842a9-11a7-4949-aca6-8633abcb1bfc)

### Mean temperature on Train data prediction - SARIMAX
Then, I tried predicting with the SARIMAX model the train data time period and this is what I got:
!![image](https://github.com/YasmineElegily/DailyClimate_TimeSeriesAnalysis_NTI/assets/69461886/30979c5b-b8af-40bd-81a0-f1ad75ebf300)


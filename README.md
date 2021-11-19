![image](https://user-images.githubusercontent.com/88399910/142641993-a5ef6237-0fbe-449b-9c6d-cf69f47618fe.PNG)
# 🌦️Temperature-Prediction-of-Indian-Cities.
Temperature Prediction using Time Series Analysis algorithm; predicting monthly average temperature using ARIMA model.

## 💭Problem Statement 
The rising average temperature of Earth's climate system, global warming, drives changes in rainfall patterns, extreme weather, arrivals of seasons, and more. 
The primary effect of **global warming** is increase in global temperature.

## 🎯Objective
Since, global warming has such major effects we try to understand the past effects of global warming (over 2009-2019) on temperature of four cities of India (Chennai, Mumbai, Delhi, Kolkata) and predict the temperature of the next twelve months using Time Series Analysis algorithm.

## 📊Dataset
In this project, the Dataset used is the famous Kaggle [Dataset.](https://www.kaggle.com/riturajsaha/temperature-of-different-cities-of-india)

This dataset contains daily temperature of four cities over 1995-2019. We modify the data to monthly average temperature over 2009-2019 using MS Excel.
## 📉Graphs

## 🗂️Pipeline of the Project
- [X] Visualisation of data
- [X] Data Preprocessing
- [ ] Establish the appropriate model
- [ ] Identify the optimal order
- [ ] Train the model
- [ ] Test the model
- [ ] Make predictions

![image](https://user-images.githubusercontent.com/72320197/135301275-a6006090-604c-4ae9-918d-4199cd76ed8b.png)


## 💥Model Used
We've used ARIMA-AutoRegressive Integrated Moving Average model.
It is a forecasting algorithm based on the idea that the information in the past values of the time series can alone be used to predict the future values.
It is a class of models that ‘explains’ a given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that equation can be used to forecast future values.
It is characterised by three terms: p,q,d where, p is the order of AR term, q is the order of MA term and d is the order of I term.

## 👩‍💻Architecture Diagram

![image](https://user-images.githubusercontent.com/72320197/135296708-e030d006-65a6-443d-81df-3a579c85ec32.png)

## 🚩Output
We aim to predict the temperature of the four cities for the next twelve months accurately.

## 💡Cheatsheets
📉[Matplotlib ,](https://www.datacamp.com/community/blog/python-matplotlib-cheat-sheet)
🐼[Pandas ,](https://www.datacamp.com/community/blog/python-pandas-cheat-sheet)
📆[Time Series .](https://math.bju.edu/media/bju-math-division/bju-math-department/math-courses/ma-415/time-series_both.pdf)


## ✍️References
[Delhi Temperature Prediction using Time Series Analysis](https://github.com/KlrShaK/Delhi-Temperature-Prediction-Time-Series-data)

[Time Series Analysis](https://github.com/ParthPathak27/Time-Series-Analysis-and-Forecasting)

[Time Series Analysis with ARIMA](https://github.com/gmonaci/ARIMA)

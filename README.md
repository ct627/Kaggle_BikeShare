# Bike Share Predictions

From [kaggle](https://www.kaggle.com/c/bike-share-predictions)

## Overview. 

Predict the number of hourly bikeshare rentals.  

The data has been split into two groups:  
training set (train.csv)  
test set (test.csv)  
The purpose is to train the training set data using machine learning algorithms to predict the number of hourly bikeshare rentals.  
data is not included in this repository but is available for download from [kaggle](https://www.kaggle.com/c/bike-share-predictions).  

## Data Dictionary
(from [kaggle](https://www.kaggle.com/c/bike-share-predictions).)
- index: record index, from the beginning of the year (1 to 8760)
- date: date
- season: season (winter, spring, summer, fall)
- year: year (0: 2011, 1: 2012)
- month: month (1 to 12) - hour: hour (0 to 23)
- holiday: if a day is a holiday or not (if a day is a regular weekend, it is still 0)
- weekday: day of the week (0 - Sunday to 6 - Saturday)
- workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
- weather: general weather conditions
   1: Clear, Few clouds, Partly cloudy, Partly cloudy
   2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
   3: Light Snow, Light Rain + Thunderstorm, Light Rain + Scattered clouds
   4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog, Apocalypse
- temp: normalized temperature, from values in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39
- feels_like: normalized chill-factor adjusted temperature, from original values in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50
- hum: normalized humidity. The values are divided to 100 (max). - windspeed: normalized wind speed. The values are divided to 67 (max).
- casual: count of casual users
- registered: count of registered users
- count: total count of bikes rented, casual + registered


## Result and code

Please see [CODE.ipynb]() for details.


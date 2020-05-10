# Restaurant Vistor Forecasting

## Background
Running a thriving local restaurant isn't always as charming as first impressions appear. There are often all sorts of unexpected troubles popping up that could hurt business. One common predicament is that restaurants need to know how many customers to expect each day to effectively purchase ingredients and schedule staff members. This forecast is challenging because of various unpredictable factors affecting restaurant attendance, such as weather and local competition. It's even harder for newer restaurants with little historical data.

## Data
The data is available at Kaggle.com and was retrieved from two separate sites:
* Hot Pepper Gourmet (hpg): similar to Yelp, here users can search restaurants and also make a reservation online
* AirREGI / Restaurant Board (air): similar to Square, a reservation control and cash register system
The data consists of reservations, visits, stores information, location, weather and holidays for over 150 restaurants in Japan. The training data covers the dates from 2016 until April 2017. The test dataset covers the last week of April and May of 2017.
 
## Project Scope
We will use reservation and visitation data to predict the total number of visitors to a restaurant for future dates. Essentially, this is a time-series forecasting problem centered around restaurant visitors. This information will help restaurants be much more efficient and allow them to focus on creating an enjoyable dining experience for their customers.
 
## Tools and Techniques
We will use RStudio for statistical inference,graphics and model creation. Also, for the time series forecasting techniques we wish to implement ARIMA, FB Prophet, Holt-Winters and timetk algorithms. Also, we might look into additional techniques as we progress through the project.

## Team Members
* Jennifer Siwu
* Sonal Mendiratta
* Manodhar Allu
* Aneesh Kalaga
* Yeji Lee

## Source
https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting/data

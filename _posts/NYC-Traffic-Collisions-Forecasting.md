-------
Title: NYC Traffic Collision Forecasting
Date: 2025-01-30
-------

This project is written in R and uses time series data to predict the frequency of traffic collisions in New York City using factors such as temperature, windspeed, precipitation, date, and others. The models created were capable of anticipating a number of traffic collisions using the cyclical trends demonstrating that certain days of the week yielded more traffic collisions than others. 

The code for this project is available here: https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/Forecasting_Final.R

The report containg more detailed information and visuals can be accessed here: https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/Forecasting_Final_Project_Report.pdf


The present cyclical trend indicated that Day 1 experiences more traffic collisions than any other day of the week on average. Day 1 is equalivant to Friday in this case. 

<div style="width: 100%;">
    <img src="https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/time-series-images/Cyclical%20Traffic%20Trend.png?raw=true" alt="Cyclical Trend where Day 1 = Friday" style="width: 50%; float: left; margin-right: 5%;">
</div>

This is evidenced further by evaulating the periodgram and harmonics of the time series. 

<div style="width: 100%;">
    <img src="https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/time-series-images/Cyclical%20Peridogram%20&%20Harmonics.png?raw=true" alt="Periodgram and Harmonics" style="width: 80%; float: left; margin-right: 5%;">
</div>

The models used were a regression model with daily dummy variables(right) and a cyclical model (left). The regression model demonstrated a ~10% error in predicting traffic collisions on a holdout sample while the cyclical model had ~14% error in forecasted predictions. 

<div style="width: 100%;">
    <img src="https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/time-series-images/Daily%20Dummies%20Forecasting%20Model.png?raw=true" alt="Left Image" style="width: 45%; float: left; margin-right: 5%;">
    <img src="https://github.com/kennedineri/nyc-traffic-forecasting/blob/main/time-series-images/Cyclical%20Forecasting%20Model.png?raw=true" alt="Right Image" style="width: 45%; float: right;">
</div>

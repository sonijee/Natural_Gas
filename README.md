# Predictions
A forecasting model for natural gas consumption can predict gas demand and make the policymakers manage the strategy for the future.
This work proposed a neural network based model to estimate the natural gas demand for upcoming months using a Long Short Term Memory network.
Based on the relevant literature and reviews from experts, some input features were identified which includes historical consumption values, average price of natural gas, average temperature, export and population of the state. These variables are closely related to the 
consumption of natural gas. 
The records were obtained over the period Jan,2001-March,2022 from different sources. The data we collected originates from U.S. Energy Information Administration (EIA) https://www.eia.gov/naturalgas/data.php
Monthly prices are measured in Dollars per Million BTU (British Thermal Unit). opulation and average monthly temperature is taken into consideration. 
Monthly population of United States is taken from Federal Reserve Economic Data (FRED)https://fred.stlouisfed.org/series/POPTHM.
The average monthly temperature of US is accessed from National Centers for Environmental Information (NCEI)https://www.ncdc.noaa.gov/cag/national/mapping/110-tavg.xml.
The Fahrenheit scale is used.
For analysis of relationship strength between different variables, a correlation matrix is used which shows correlation coefficients between input features. Values near -1 indicates the negative linear correlation while
0 represents no correlation between two attributes.  Values near 1 indicates the positive linear correlation. 
![hmap](https://github.com/sonijee/Predictions/assets/136623761/d8f65896-78b0-4ef1-9e7e-42182b38c086)


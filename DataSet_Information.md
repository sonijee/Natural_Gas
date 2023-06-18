Based on the relevant literature and reviews from experts, some input features were identified which includes historical consumption values,
average price of natural gas, average temperature, export and population of the state. These variables are closely related to the 
consumption of natural gas. 
The records were obtained over the period Jan,2001-March,2022 from different sources. The data we collected originates from U.S. Energy Information Administration (EIA) https://www.eia.gov/naturalgas/data.php
Monthly prices are measured in Dollars per Million BTU (British Thermal Unit). opulation and average monthly temperature is taken into consideration. 
Monthly population of United States is taken from Federal Reserve Economic Data (FRED)https://fred.stlouisfed.org/series/POPTHM.
The average monthly temperature of US is accessed from National Centers for Environmental Information (NCEI)https://www.ncdc.noaa.gov/cag/national/mapping/110-tavg.xml.
The Fahrenheit scale is used.
![table1](https://github.com/sonijee/Predictions/assets/136623761/223b7694-eaec-4e0a-bcea-d15de854b32b)

The date attribute is first transformed into mm-dd-yyyy format and used as an index column
of the dataframe. The data from various sources has been
merged into single Comma Separated Values (CSV) file for the
further processing. The features of our dataset is described in
the Table above. Data has been collected at an monthly frequency.
The features Price, Temperature, Population, Export and Consumption are considered as input for the time series forecasting. As output, monthly consumption of natural gas is 
considered. There are 255 datapoints in our dataset in which
last 12 months are used as test set for predicting the 12 months
consumption values.



For analysis of relationship strength between different variables, a correlation matrix is used which shows correlation coefficients between input features. Values near -1 indicates the negative linear correlation while
0 represents no correlation between two attributes.  Values near 1 indicates the positive linear correlation. 
![hmap](https://github.com/sonijee/Predictions/assets/136623761/d8f65896-78b0-4ef1-9e7e-42182b38c086)



Corelation figure shows the matrix that visualize the linear relationship between different variables. The correlation coefficient
for Consumption and Temperature as shown in Figure 10 is
-0.69 which shows strong negative relationship between the
two variables. When monthly average temperature goes down,
monthly consumption rises means consumption is higher in
colder months than the hotter months. Consumption and population correlation value 0.51 shows the positive association
among these two features depicts that the demand will keep
increasing as the population increases.


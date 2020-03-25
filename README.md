# Miami-Public-Transit

Ironhack's final project 

This project uses data from the National Transit Database to predict bus and rail ridership in Miami-Dade County. 
The data is from January 2002 - January 2020, and a SARIMAX model is used to predict until December 2021. 

The data needs minimal cleaning, only a groupby for Miami-Dade county and Bus or Rail, and to transpose the data. 
The index is a datetime index, as needed for time series modeling. 

Hurrican data can be seen for October 2005 and September 2017, and it is averaged out to reduce outliers. 

A Grid Search was used to find the best parameters for the SARIMAX. 

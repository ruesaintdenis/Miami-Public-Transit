# Miami-Public-Transit

Ironhack's final project
Time Series Analysis

To view the presentation, with data visualizations done on Tableau, please follow this link: 

https://drive.google.com/file/d/1sIANC54rxVFOnM3HOGYXUgHJjk0ERfeL/view?usp=sharing


This project uses data from the National Transit Database to predict bus and rail ridership in Miami-Dade County. 

The data is from January 2002 - January 2020, and a SARIMAX model is used to predict until December 2021. 
The variable being measured is Unlinked Passenger Trips, which accounts for each time a passenger uses either the bus or the rail. For example, a passenger may have a trip that requires 2 buses and 1 train to complete. This will result in 2 unlinked trips for the bus, and 1 unlinked trip for the train. 

The data needs minimal cleaning, only a groupby for Miami-Dade county and Bus or Rail, and to transpose the data. 
In addition, hurricane data can be seen for October 2005 and September 2017, and it is averaged out to reduce outliers.
The index has been changed to a datetime index, as needed for time series modeling. 

A Grid Search was used to find the best parameters for the SARIMAX. 

For the theoretical justification and tableau data visualizations, please see document on google drive linked above.
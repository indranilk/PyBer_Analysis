# PyBer_Analysis

Overview of Analysis:

The purpose of the module was to analyze the ride sharing data of three different type of cities including urban, suburban, and rural cities. We had two csv files with city data and ride data. The city data file had each city, driver count, and type of city. The ride data file had the city, date, fare, and ride_id. We created a dataframe out of both sheets and then made a single dataframe out of both dataframes. We then created a summary dataframe of the total rides, total drivers, total fares, average fare per ride, and fare per driver for all city types. We then created a new dataframe to  calculate weekly fares for all city types. After resampling the data, we could create a plot of the new dataframe of total fares by the city type.

 Results:
 ![image](https://user-images.githubusercontent.com/8925001/120966552-3dcfb900-c71b-11eb-9cfc-a7b71e107d71.png)
 
This dataframe shows the total rides, drivers, fares, and average fare per ride and average fare per driver. Urban cities had most number of  total rides, total drivers, and total fares while rural cities had least number of total rides, total drivers, and total fares. Urban cities however had the lowest average fare per ride and average fare per driver while rural cities had the highest average fare per ride and fare per driver. 

![image](https://user-images.githubusercontent.com/8925001/120966686-6b1c6700-c71b-11eb-9da5-b66f03a98a59.png)

As you see from the PyBer summary graph, the urban cities have the highest total weekly fare and the rural cities have the lowest total weekly fare. 

Summary

Some recommendations to the CEO would be to balance out the driver count, balance the fare amount, and get rid of Nans from the dataset. The difference in the driver count and fare amount creates a big imbalance in the average fare per ride and drivers. Getting rid of Nans is also necessary as that can cause outliers in the data and really high fares in one city type compared to another.

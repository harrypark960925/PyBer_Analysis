# PyBer Analysis

## Overview of the analysis 
The purpose of the analysis is to create a summary DataFrame of the ride-sharing data by city type. Once we find our data, we created multiple-line graph that shows the total weekly fares for each city type. After merging two files into one dataframe, we used groupby() function to pull up the total rides, total drivers, and total fares from each city type. Then, we were able to calculate the average fare per ride and average fare per driver. Once we gathered all the computational data, we have created new dataframe that summarizes the dta we have calculated and re-formatted the columns. We then used pivot() function to set 'date' as an index, 'type' as a column, and 'fare' as a value and created a multiple line graph that shows the total fare by city type for each week between the time period of '2019-01-01' and '2019-04-29'.

## Results
<img width="613" alt="Screen Shot 2022-03-27 at 5 47 25 AM" src="https://user-images.githubusercontent.com/83077836/160275977-253dc372-eb5b-41ce-9573-0e889bbbcc69.png">

- Rural cities have the least amount of total rides, drivers, and fares. 
- Suburban cities are at the 2nd place for total rides, drivers, and fares. 
- Urban cities have the most amount of total rides, drivers, and fares. 
- Rural cities have the leaset amount of total rides, drivers, and fares but has the most average fare per ride and average fare per driver. 
- Urban cities have the most amount of total rides, drivers, and fares but has the least average fare per ride and average fare per driver. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/83077836/160276094-1fe19093-08f0-4f3d-86c9-a5dff00387dc.png)

## Summary
Based on our data, we can see that the fares are so different by the city type. By looking at the weekly total fare graph for each city type and summary table, we can see that the price of fare will be totally different by where the clients are living. By summary, we can say that the rural cities are commanding a high fare since there are few drivers for the ride and the distances and travel time are tend to be longer than other city types. Thus, the following three are the recommendations to the CEO for addressing any disparities among the city types.
1. In urban cities, charge more fare per mile since the distance and travel time are shorter than other city types so that the drivers can earn more per ride.  
2. Based on the city type, make a difference in number of drivers (either increase or decrease it) based on the number of rides per week. 
3. Assign some drivers to either suburban or rural cities to decrease the number of drivers in urban cities and increase the average fare per driver. 

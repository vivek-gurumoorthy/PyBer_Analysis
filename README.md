# PyBer_Analysis

## Overview:
Pyber, a ridesharing service, would like to gain insight into the current state of its business. Using data on both individual Pyber rides as well as Pyber rides being used in each city, we can perform analysis on the number of rides, number of drivers, prices of Pyber rides, and more as a whole. 

Beyond doing an analysis of all aggregated Pyber data, we can try to understand how the type of city, whether urban, suburban, or rural, may affect the use of Pyber as well as other measures such as number of drivers and ride price.

## Results: 

<p align = "center">
  <img width="767" height="500" src="https://user-images.githubusercontent.com/108832056/185262305-d154bdf4-5549-4db3-8fee-747d7f8148ac.png">
</p>

This figure compares the total number of rides, average fare, and number of available drivers between the three different city types. The x-axis represents total rides per city, the y-axis represents average fare of a ride, bubble size represents the number of available drivers in the city of interest, and bubble color is determined by whether the city is either urban, suburban, or rural. 
Clearly, average ride fare is the highest, generally, in rural cities, second-highest in suburban cities, and lowest in urban cities. Additionally, number of total rides is the highest in urban cities, second-highest in suburban cities, and lowest in rural cities. Finally, total driver count is highest in urban cities, second-highest in urban cities, and lowest in rural cities.

![image](https://user-images.githubusercontent.com/108832056/185385927-254ad8d3-2072-48cf-b10d-f4fcf7d40da9.png)

The DataFrame above depicts the aggregation of all Pyber data by each city type. Breaking it down by each city type, some trends begin to appear. Urban cities have the most total rides, total drivers, and total fares while having the lowest average fare per ride and average fare per driver. Meanwhile, rural cities have the highest average fare per ride and average fare per ride while having the least total rides, total drivers, and total fares. Suburban cities have the middle value in all of these statistics. This suggests that average fare per ride and average fare per driver are negatively correlated with the total drivers, as cities that generally have more drivers such as urban ones have significantly lower costs per ride and per driver. Additionally, and unsurprisingly, this data suggests a positive correlation between total drivers and total rides and total fares collected. 

<p align = "center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/108832056/185262443-9a195c84-eabf-4dc6-b7b5-66d890b3601c.png">
</p>

This figure, tracking fares accumulated from Pyber use over the course of the beginning of January 2019 to the end of April 2019, demonstrates some trends. First and foremost, as seen with nearly all other statistics, Pyber use is inherently highest in urban cities, second-highest in suburban cities, and lowest in rural cities. This, perhaps in part due to a significantly higher number of total drivers as identified above, results in the fares being accumulated from each city directly aligning with this hierarchy. Despite some fluctuations in data, the fares accumulated by urban Pybers far outmatch those accumulated by suburban Pybers, and likewise the fares accumulated by suburban Pybers dwarf those accumulated by rural Pybers. Despite charging far more for rural and suburban Pyber rides, these tremendous gaps in earnings suggest that those in rural areas may be less inclined to use this service, perhaps suggesting an opportunity for outreach to these rural areas. 


## Summary: 
Three recommendations
1. Rather than having employees only drive in a specific city, Pyber could potentially give drivers the option of being assigned a gegraphic area that includes a few different cities, preferably of varying categories, and have the city in which they drive for the day rotate. This could potentially increase the number of available drivers in rural cities and make the average ride fare in those locations more affordable for customers.
2. To incentivize driving in rural areas, Pyber itself could pay an additional sum to drivers who mostly service rural areas and make rural customers pay less disproportionately large fares. This would incentivize more drivers to service these rural areas and make customers less hesitant to pay the normally high fare prices.  
3. Finally, more data should be collected as to how the time of year affects Pyber use across these city types. While 4 months of weekly usage data is good to start forming ideas of trends, more needs to be collected. If there are clearly weeks or months with substantial usage increases across all three city types, these may be good times to provide added benefits to drivers to meet added customer demand. 

# PyBer_Analysis
 
## Overview of Analysis
This analysis’ goal is to create a multiple-line graph that shows the total weekly fares for each city type: urban, suburban, and rural. For this challenge, I created a summary data frame that combined total rides, total drivers, total fares, average fare per ride, and average fare per driver and plotted it on a  multiple line graph.

## Results
Once the summary data frame is created, the trend between city type, the total number of rides, total fare, and total number of drivers becomes evident. The total number of rides, fares and drivers decreases from Urban to Suburban to Rural communities, while the average fare per rider becomes greater. This may be skewed by the average distance per ride, thereby affecting the fare per ride, however the data is clear that with less drivers in rural communities, the average fare per driver increases as the overall supply of drivers is low - even when normalized for demand. By plotting this data on the multiple line chart we can visualize the total fares by city type over five months. With the exception of an outlier peak of suburban rides in the month of April, the city types trend similarly from month to month, peaking in February and fluctuating throughout this period.
![Fig8](https://github.com/craig-clemens/PyBer_Analysis/blob/main/analysis/Fig8.png)

## Summary
Three conclusions could be surmised from this data. One is that the peak in fares in suburban cities in April is clearly an outlier. However, there might be an external factor pushing up overall ridership in suburban areas during this time of year. It would serve Pyber to investigate this to see if this is either random or if there is a predictable increase in demand during this time period.

Secondly, with a decreased supply of drivers the average fare per ride increases. Although this may make it easier for Pyber to achieve it’s profit goals, they do not want demand to completely outstrip supply insofar that potential rides end up looking for other ride-sharing services. This is a delicate balance that must be examined further. 

Finally, rural drivers are by far the most profitable. However, should supply suddenly outstrip demand, there would be way too many drivers for the amount of rides. Although urban and suburban fares are lower by average, the trips are likely shorter and there are far more of them per driver. This balance is precious and if changed, could severely alter the profitability of these rural cities if urban drivers start taking rural clients.

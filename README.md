# PyBer_Analysis
## Overview and Purpose of Analysis
The purpose of the PyBer Analysis was to not only analyze, but create visual summaries of PyBer's ride sharing data. This analysis uses Python and Pandas to create a summary DataFrame of the ride-sharing data by city type. Using Pandas and Matplotlib, we can create multiple-line graphs that shows the total weekly fares for each city type (Urban, Rural, and Suburban).

Matplotlib allows us to chart our data and learn new trends relating to the ride sharing data. Speciffically, we can learn how the data differs by city type and how those differences can be used by decision-makers at PyBer. Using these dataframes and visual represenatations helpss us learn the differences in ride-sharing data among the different city types.

## Results
After analyzing all the ride sharing data, we can summarize our key findings into a Dataframe:

![Ride_Share_City_Type](/analysis/ride_share_summary_city_type.png)

### Rural vs Surburban vs Urban
Based on the PyBer ride sharing data, Rural areas provide the highest average fare per ride with $34.62. Therefore, it also provides the highest average fare per driver with $55.49. However, the total fares for Rural came out to only $4,327.93 due to only 125 total rides.

On the other hand, there were 1,625 total total rides in Urban areas. While Urban areas grossed the highest total fare ($39,854.38), it's average fare per ride and driver were the lowest at $24.53 and $16.57 respectively. We can better understand this average fare discrepancy by looking at this multiple-line chart:

![Ride_Share_Summary_Chart](/analysis/PyBer_fare_summary.png)

Analyzing the total fares by city type over the last year helps us better understand how much revenue is made in each city type. Looking at this line chart, it's evident that each city type remained fairly static in its average fare through the first four months of 2019. Urban was the highest averaging above $1,500 and below $2,500. Suburban stayed in the middle averaging etween $600 and $1,500. Finally, Rural stayed above $0 but never exceeded $500.

## Summary and Recommendations
These findings make sense given the demand for each city type. It's evident taht Rural places have not only higher fare prices, but also less drivers available due to the city type. There is not as much demand for ride sharing in rural cities as there are in Urban areas. One key recommendation based on this research would be to hire more dirvers in Rural areas. This increased supply will end up bringing the demand down and in turn create lower fare prices. The steep average fare price in a rural areas disinsentivises people from ride sharing.

Another recommendation Pyber could easily implement is to increase the total fares for Rural areas with more dirvers. The total fares in Rural areas accumulated to $4,327.93 which is almost a tenth of the total fares from urban areas ($39,854.38). To crate a more balanced revenue structure for each city type, increasing the supply of drivers for Suburban and Rural areas will bring down the average price, but it will create more revenue overall with more rides being completed. Also, the lower average fare rate incentivises more rides to be used through Pyber.

A final recommendation directly relates to the disparity among these city types. The amount of Urban city drivers as the excess supply of drivers is clearly driving down the average fare price. There are more than 30x Urban drivers (2,405) as there are Rural drivers (78). Incentivizing some of these drivers to drive in Rural places would not only increase the much needed supply of drivers in Rural areas, but it will also increase the demand for drivers in Urban areas. this would drive the average fare price up in Urban areas which will benefit the drivers and Pyber.
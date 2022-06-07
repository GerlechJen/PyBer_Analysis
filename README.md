# PyBer Analysis
## Overview 
As a new data analyst for PyBer, a python-based ride-sharing app company, I was asked to perform exploratory analysis on data from January to early May of 2019. The rideshare data is in very large CSV files . To aid the exploratory process, I created several types of visualizations that told a compelling story about the data. I wrote python scripts using pandas libraries, Jupyter notebook and matplotlib to create various charts that showed the relationship between the type of city and the number of drivers and riders, the average fare based on the total number of rides and drivers per city, as well as the percentage of total fares, riders, and drivers by type of city. The analysis and visualizations I created helped PyBer improve access to ridesharing services and determined affordability for undeserved neighbourhoods.

In this project, continuing further with my exploratory analysis, I will be creating a summary DataFrame of the ride-sharing data by city type. I will also create a multiple-line graph that shows the total weekly fares for each city type between the months of January and April 2019. Finally, I will submit a written report that summarizes how the data differs by city type and how the differences can be used by decision-makers at PyBer.

## Results 
![image1](https://github.com/GerlechJen/PyBer_Analysis/blob/main/Analysis/PyBerDataFrame.png)

From the PyBer summary dataframe above, the following conclusions can be drawn from our analysis:

* The urban city type had the highest number of total rides at 1,625 followed by the suburban city type at 625	total rides. The rural city type had the least number of total rides at 125.

* When it comes to the total number of drivers, a similar trend was obesrved. The urban city type had the highest number of drivers  at 2,405 followed by the suburban city type at 490 drivers. The rural city had the least number of drivers at 78.

* The total fares accumulated by each city type followed the same pattern. The urban city type generated $39,854.38, suburban city type generated $19,356.33 and rural city type generated just $4,327.93. 

* For average fare per ride, rural cities had the highest at $34.62. Suburban cities had the second highest average fare per ride at $30.97, and urban cities had the lowest average fare per ride at $24.53.

* Rural cities had the highest average fare per driver at $55.49. Suburban cities had the second highest average fare per driver at $39.50, and urban cities had the lowest average fare per driver at $16.57.

![image2]

When we look at the above multiple-line chart, we are able to see what the total fares were on a week to week basis for each city type. Overall, from January to April, the total fare for the rural areas were always the least.This implies that in total, small amount of money is generated from the rural city type despite it having the highest average fare per ride. The total fares for the urban city type are always the highest throughout January to April while the total fares generated in the suburban city type always lie between the rural and urban cities total fares.  


## Summary
I went further to find the ratio of total rides to total drivers for each city type. The ratio of rides to drivers for urban cities was 1:1.48. That of suburban cities was 1: 0.784 and rural cities had a ratio of 1: 0.624. This shows that the urban cities have a higher number of drivers available per ride followed by the suburban cities.The rural cities have few drivers available per ride making them attract higher fare charges. The principle of demand verses supply is evident here.

Based on the overall results of the analysis, I will like to recommend that:

1. The fares for the rural and suburban cities be reduced. The fares for these locations are higher compared to the urban cities. A reduction in fare could increase patronization of riders in these cities. 
2. You expand the business in the rural and suburban cities by increasing the number of drivers so that they would have a ratio of drivers to rides similar to that of the urban cities. This could end up reducing the fares in the rural and suburban cities as the demand verses supply will be more balanced. 
3. During certain months or holidays, some form of promotion is organized. It could be giving discounts on ride fares. This would encourage more people to patronize during those times and even bring on board new riders. 

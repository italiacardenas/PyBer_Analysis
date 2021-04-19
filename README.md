# PyBer Analysis

## Overview of the PyBer Analysis
This is an exploratory analysis for PyBer, a python based ride sharing company. For this analysis PyBer's ride sharing data from January through end of April for the year 2019 was used. The purpose of this analysis is to improve help Pyber improve access to ride sharing services by determinging affordability for underserved cities. Provided are charts that showcase the relationship between the type of city and the number of drivers and riders as well as charts that represent the percentage of total fares, riders, and drivers by type of city. 

The process was created by data inspection, merging data sets, performing various calculations, and creating data series and dataframes. To execut ethe analysis Python 3.7.6, Anaconda 4.9.2, Matplotlib 3.3.2, Jupyter Notebook, and Pandas libraries were used.

## PyBer Analysis Results 
- **PyBer Summary DataFrame** 
![summarydataframe.png](https://github.com/italiacardenas/PyBer_Analysis/blob/ca6aff57f9c72cfac747f28dab53d8889741735f/readmescreenshots/summary_dataframe.png)

The Pyber Summary DataFrame shows that the cost to use PyBer in rural cities is significantly higher for the user, most likely due to the lower amount of total drivers and total rides. The average fare per driver is roughly 3 times lower in urban cities. The demand for rides in urban cities is 13 times that of a rural city.The summary dataframe also shows that urban cities are the only ones where the total drivers outweigh  the total rides whcih explains why the average fare per driver in urban cities is so low. 

- **PyBer Fare Summary Chart:** 
![Pyber_fare_summary.png](https://github.com/italiacardenas/PyBer_Analysis/blob/55598d7663b358d387f8314ea67175cf6990647d/analysis/Pyber_fare_summary.png)

Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
The PyBer Fare summary chart shows the trends in fare prices for the mo0nths January to April in 2019. The chart shows spikes in fare for all three city types during late February and dips in all three for the fare prices befor ethose spikes. The total fare for rural cities is significantly lower than total fares for urban and suburban. With the exception of th espike in April, rural cities total fare remains just under 500. After the spike the three experience in late February, suburban cities' total fare seems to decline and stay under 1500 and begins to spike again late rin April. Contrary to the trend in suburban cities for late April, urban cirties' total fare begins to decline during that period. Urban total fare ifluctuates the most with various quick increases and decreaes during the month of March. 

## PyBer Analysis Summary
Three business recommendations to the CEO for addressing any disparities among the city types.:
1. Limit the number of drivers in urban cities. The total number of drivers in urban cities is almost 1.5 times greater than the total rides. This causes the urban driver to make less per ride, while dealing with a lot of other factors ie, traffic, city people.
2. Encourage more ride sharing in rural areas. The total rides for the months of January - April for rural cities is 30 times less than urban cities and 6 times less than suburban areas. If PyBer could be the first ride sharing company to change this trend, they would be ahead of the game! 
3. One way to try and balance the disparities would be by encouraging drivers in Urban areas to work in suburban areas.


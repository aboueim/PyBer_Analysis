# PyBer_Analysis

## Overview of Analysis

In this project, I aim to analyze ride-sharing data using several python libraries such as pandas and matplotlib to obtain new insights to be utilized by a company CEO. In doing so, I will create a summary dataframe in which ride-sharing fares data is shown given the type of city (i.e., rural, suburban, and urban) in which the rides were given. Besides, I will restructure the dataset using pivoting and resampling to achieve new dataframes required to visualize time-series data, which allows for comparing ride-sharing data between different city types during a specific timeframe. The results of these analyses will help firm decision-makers to make more insightful decisions based on the disparities found within ride-sharing data, given the time and location.

## Results

The line chart below displays the ride-sharing graph for three types of cities: rural, suburban, and urban, from 2019-01-01 to 2019-04-28. The lines reveal almost similar patterns overall (except for slight differences in minor fluctuations; for example, while ride-sharing fares in urban and suburban cities increase in early January, it decreases for rural cities. Besides, all ride-sharing fare values for the three city types fluctuate slightly and show minor peaks in this period (In late February for all three, and another rise for rural cities' sum of fares in early April). However, the total fares for each type of city differ meaningfully along this timeframe. While rural cities' total fares vary between 0 to 500 $USD in this period, total fares for suburban cities and urban cities fluctuate between 700 to 1500 and 1600 to 2500 $USD, respectively. The total fare revenues indicate that cities in urban areas performed much better than the other two regional locations in terms of total income produced during this period.


![This is an image](/Analysis/PyBer_fare_summary.png)


Nonetheless, the graphical presentation above does not provide information about the profitability of ride-sharing per ride or for each driver. Looking at the  table below, we realize that urban cities' overall profitability is mainly due to the much larger number of drivers (1625, 625, 125, respectively, for urban, suburban, and rural areas) and rides given (2405, 490, 78, respectively, for urban, suburban, and rural areas) in these areas rather than per-ride fares charged. Alternatively, the per-ride fares charged are reversely ordered; that is, rural city rides were more profitable ($ 34.62 per ride) than suburban ($30.97) and urban ($24.53) city rides. Furthermore, rural city drivers also earned more money ($55.49 per driver) compared to suburban ($39.5) and urban ($ 16.57) city drivers on average in this period. These findings allude to the fact that while urban account for most of this ride-sharing company's revenue, drivers working in the rural areas gain more money per ride they give.

![This is an image](/Analysis/Fares_Detail_Table.png)

## Summary

Based on the findings in the Results section, there are apparent disparities in ride-sharing profitability given the city type, average fares charged per ride, and gains per driver. My suggestions for the CEO, given the discovered differences, are:

1. The competitive ride-sharing economy in rural areas could be alleviated by controlling the number of new drivers recruited. The rides per driver are much lower in urban areas than in the other two (although inactive drivers may contribute to this number) city types; thus, even in the case of similar pricing models, driver gain would be less. This strategy may be helpful to ensure the profitability of both the ride-sharing economy in urban (and suburban to less extent) areas as well as drivers' satisfaction in the long run.

2. Given that most ride-sharing revenues are obtained in urban areas, the budget allocations (e.g., infrastructure, app development, customer service operations) should be adjusted based on the revenue proportions to secure market share. Nonetheless, it does not mean the company should neglect less profitable areas but consider more specialized plans (e.g., unique services for rural or suburban areas).

3. Finally, the findings also indicate a need for holding a balance between the company's total revenue and drivers' gain. To compensate for the lower gains of urban drivers, the company can modify its share based on city type. For example, a higher share rate for rural and lower shares in urban areas per ride (assuming the overall income for the company is not reduced remarkably) could be another strategy to fill the existing gap.


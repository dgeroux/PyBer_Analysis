# PyBer_Analysis
Click here to view the analysis file: [PyBer_Analysis](https://github.com/dgeroux/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Overview of Analysis
PyBer is a python-based ride-sharing company that needs help analyzing their business data. The main deliverables of this analysis is to create a ride-sharing summary DataFrame by city type and generate a multiple-line chart of total fares for each city type. PyBer operates in three types of cities: urban, suburban, and rural. Previously, I analyzed the ride count, driver count, fare count, average fare per ride, and average fare per driver, all categorized by the type of city. The purpose of this analysis is to identify how the data differs by city type and recommend how those differences can be used by decision-makers at PyBer.

## Results
### Deliverable 1
![deliverable_one](https://github.com/dgeroux/PyBer_Analysis/blob/main/deliverable_one.png)
From the summary data frame, we can see that there is a trend between how populated a city is and the total number of rides, which directly affects the total number of drivers, total fare, and both averages. Although the total number of rides, drivers and fares decrease as the cities become farther from urbanized areas, the average fare per ride and per driver seems to increase. This can be explained by the accessibility of PyBer rides and drivers in rural areas. Less drivers in rural areas will may lead to a higher average fare per ride and driver, as prices increase when supply is low. 
![deliverable_two](https://github.com/dgeroux/PyBer_Analysis/blob/main/deliverable_two.png)

With the multiple-line chart, we are able to compare total fares by city type over a period of five months. The number of rides seem peak at the end of February and fluctuates during the month of March. All the graphs tend to follow the same trend throughout these months, except for the trend in suburban cities, where we see a sharper increase during the month of April. 
![Fig8](https://github.com/caseychen3605/PyBer_Analysis/blob/main/Analysis/Fig8.png)

## Summary
Since the total fare by city type seems to increase during the month of April in suburban cities, the company should research as to what causes this increase, especially because the total fare decreases for other types of cities. 

Additionally, we know that average fare per ride and driver is higher when there are less drivers. With this information, the company can influence ride-share prices by limiting or increasing the number of drivers during a certain time to achieve its profit goal. 

Lastly, the average fare per ride shows a gradual increase from more populated cites to less populated cities. However, the average fare per drive increases drastically when following the same trend. This indicates that the number of drivers may be exponentially lower than expected. The company may want to allocate more drivers to rural areas to optimize its profits. 


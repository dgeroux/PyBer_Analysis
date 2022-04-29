# PyBer_Analysis
Click here to view the file: [PyBer_Analysis](https://github.com/dgeroux/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)

## Overview of Analysis
PyBer is a python-based ride-sharing company that needs help analyzing their business data. The main deliverables of this analysis is to create a ride-sharing summary DataFrame by city type and generate a multiple-line chart of total fares for each city type. PyBer operates in three types of cities: urban, suburban, and rural. Previously, I analyzed the ride count, driver count, fare count, average fare per ride, and average fare per driver, all categorized by the type of city. The purpose of this analysis is to identify how the data differs by city type and recommend how those differences can be used by decision-makers at PyBer.

## Results
### Deliverable 1
![deliverable_one](https://github.com/dgeroux/PyBer_Analysis/blob/main/deliverable_one.png)
### Deliverable 2
![deliverable_two](https://github.com/dgeroux/PyBer_Analysis/blob/main/deliverable_two.png)

These results make perfect sense and are exactly what I hypothesized. Urban cities are densely populated, which translates into more rides, more drivers, more revenue in total, lower average fare per ride (passenger destinations are closer in urban areas), and lower average fare per driver (again, shorter trips in urban areas). The data from Rural cities proves the same point but from the other side of the spectrum. Rural cities are lightly populated, meaning less rides, less drivers, less revenue in total, higher average fare per ride (passenger destinations are more spread out in rural areas), and higher average fare per driver (again, longer trips in rural areas). By definition, a 'suburban' city isn't quite as densely populated as urban cities and also not as lightly populated as rural cities - it's right in the middle, which is exactly what the data shows in the DataFrame.

## Summary
In urban cities: 2,405 drivers were responsible for 1,625 rides during this time frame, which equates to 0.68 rides per driver (some drivers never completed a ride).
In suburban cities: 490 drivers were responsible for 625 rides during this time frame, which equates to 1.28 rides per driver.
In rural cities: 78 drivers were responsible for 125 rides during this time frame, which equates to 1.69 rider per driver.

More drivers = more rides 
More rides = more revenue (for both the drivers and the company)

Based on the results, here's three business recommendations:
1. PyBer needs to directly incentivize its surplus of urban drivers to start doing rides in suburban and rural areas. This will increase the number of drivers in these areas, which will increase the amount of total rides and total revenue for these respective areas. 
2. Each city type saw a spike in rides (which equates to a spike in revenue) toward the end of February - drivers need to be allocated to the different city types in a way that capitalizes on this increase in demand during that time. 
3. Generally speaking, the multi-line chart shows us that warmer weather equates to higher demand (more rides ; which we know means more money!). Marketing promotions need to be devised during the colder months to boltser (or counteract) the low demand/low revenue. On the flipside, different marketing promotions need to be devised during warmer months to support and take advantage of the higher demand/higher revenue. 


# Individual-Project-Final-Version
Data Viz

# Background
On the condition that 800 of 3,000 vechile-pedestrian collisions involved children, Chicago government rolleded out Children's Safety Zone Program to protect children and other pedestrains by ticketing speed vialotions around school and park areas. The program started in late 2014 and kept running till now. To evaluate the program's effect on speeding behavior, I use the [dataset](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4) that records speed violation for each camera from 7/1/2014 to 4/11/2019.

## Finding 1: The program is effective: the number of speed violations has been decreasing over the years.
The biggest question is if the program is effective on slowing down motorists and reducing speeding behaviors. Thus, I plot the average violations by week and found the decreasing trend over the years. To better illustrate the trend, I added a trend line and it confirmed my initial impression.

![Trend](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Trend%20Dashboard.png)

The declining trend indicates that the program is effective on speed violation behaviors. The message to the mayor is clear: with the program, children's safety on the road around schools and parks is enhanced. Also, so far, since the average violations by week is always on the decline year by year, there is no evidence that the program has reached its limit on the effectiveness. The program should keep running under current polices and actions. If, in the future, the declining trend stops, the city may start additional acts to improve the safety.

## Finding 2: The speeding behavior has seasonality.
After evaluating the effectiveness of the whole program, I want to explore if the speeding behavior is assoicated with the time of the year and the possibilities to adjust the policy accordingly. Thus, I plot the average violations by month. As shown on the graph, for each year, the number of average violations is relatively lowest in January, then it keeps increasing till July and August and starts decreasing till the end of the year, back to the January level. There is an obvious seasonality of speeding behavior. 

![Seasonality](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Seasonality%20Dashboard.png)

However, the number of violations in July and August cannot be treated as in other months. There is no school for children in these two months. Knowing that, drivers might think it is of no use obeying the traffic rules around schools and break the speed limit. Thus, the peak in July and August is questionable and cannot represent the driving behavior under the normal Safety Program conditions. But still, despite July and August, we can still see a trend of more violations in hotter months.

![Seasonality (excluding July and August)](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Seasonality%20Dashboard%20-%202.png)

The median reference line is there to support and cross-validate the declining trend.

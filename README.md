# Individual-Project-Final-Version
Data Viz

# Background
On the condition that 800 of 3,000 vechile-pedestrian collisions involved children, Chicago government rolleded out Children's Safety Zone Program to protect children and other pedestrains by ticketing speed vialotions around school and park areas. The program started in late 2014 and kept running till now. To evaluate the program's effect on speeding behavior, I use the [dataset](https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4) that records speed violation for each camera from 7/1/2014 to 4/11/2019.


# Findings
## Finding 1: The program is effective: the number of speed violations has been decreasing over the years.
The biggest question is if the program is effective on slowing down motorists and reducing speeding behaviors. Thus, I plot the average violations by week and found the decreasing trend over the years. To better illustrate the trend, I added a trend line and it confirmed my initial impression.

![Trend](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Trend%20Dashboard.png)

The declining trend indicates that the program is effective on speed violation behaviors. The message to the mayor is clear: with the program, children's safety on the road around schools and parks is enhanced. Also, so far, since the average violations by week is always on the decline year by year, there is no evidence that the program has reached its limit on the effectiveness. The program should keep running under current polices and actions. If, in the future, the declining trend stops, the city may start additional acts to improve the safety.


## Finding 2: The speeding behavior has seasonality.
After evaluating the effectiveness of the whole program, I want to explore if the speeding behavior is assoicated with the time of the year and the possibilities to adjust the policy accordingly. Thus, I plot the average violations by month. As shown on the graph, for each year, the number of average violations is relatively lowest in January, then it keeps increasing till July and August and starts decreasing till the end of the year, back to the January level. There is an obvious seasonality of speeding behavior. The median reference line is there to support and cross-validate the declining trend.

![Seasonality](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Seasonality%20Dashboard.png)

However, the number of violations in July and August cannot be treated as in other months. There is no school for children in these two months and kids are mostly likely not in schools or parks as usual. Knowing that, drivers might think it is of no use obeying the traffic rules around the protected areas and they break the speed limit. Thus, the peak in July and August is questionable and cannot fully represent the driving behavior under the normal Safety Program conditions. But still, despite July and August, we still can see a trend of more violations in hotter months.

![Seasonality (excluding July and August)](https://github.com/JinjinJanelle/Individual-Project-Final-Version/blob/master/Seasonality%20Dashboard%20-%202.png)

There are two reasons. The road condition in colder months, especially winter naturally slows down the speed that people drive at. Also, nice weather makes people hard to focus while driving ([Hum by Verizon](https://www.prnewswire.com/news-releases/new-survey-from-hum-by-verizon-suggests-41-percent-of-drivers-struggle-to-stay-focused-during-the-summer-more-than-any-other-time-of-year-300656063.html), 2018). Thus, the tendency of more violations in June, May, and September in dataset is true.

I think the message to mayor is twofold. First, the high number of violations in July and August is present, but, the threat to childrens' danger is not as bad as it would be, because children are highly likely not around the camera areas. Second, there is more speeding behavior in hotter months when children still attend school. The city can take different approaches in these months. In July and August, they can loose the speed limit to some extent without introducing very dangerious speeding incidents around protected areas. In hotter months such as May, June and September, they can take actions to help motorists stay focus around schools and parks, for example, adding temporary warning signs or roadblocks.


## Finding 3: The speeding behavior has seasonality.






Reference:
https://www.prnewswire.com/news-releases/new-survey-from-hum-by-verizon-suggests-41-percent-of-drivers-struggle-to-stay-focused-during-the-summer-more-than-any-other-time-of-year-300656063.html

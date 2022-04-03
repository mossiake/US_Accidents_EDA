# US_Accidents_EDA
Exploratory Data Analysis on US Accidents in Python

The dataset can be found on kaggle: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents?datasetId=199387&sortBy=voteCount

This dataset provides data about accidents in the US between February 2016 and December 2021 and covers 49 states. It is a very large dataset with around 2.8 million records. The information in this dataset can be useful to learn more about accidents in the US and possible factors behind those accidents. This can also be useful for accidents prevention.
Through an EDA in Python, I was able to obtain several valuable insights on US accidents which I will be sharing below.
Before presenting my insights, it is important to note that the state of New York (NY) was omitted from the dataset. As NY and particuly New York City are not present, the data fails to represent accidents in one of the most populated area of the US.

Location

The number of accidents seems to be higher on the coastal parts of the US as highlighted by the heatmap. Further analysis reveals that the state with the highest number of accidents is California, which is on the West coast. Other states with a high number of accidents include Florida and Texas. 
In terms of cities, the ones with the most accidents are Miami, Los angeles, Orlando, Dallas, and Houston. Those cities are part of the states with the highest number of accidents. However, it is important to note that despite California being the state with the highest number of accidents, it is actually the state of Florida that has the number one city in terms of accidents. Indeed, Miami is listed first and Orlando is listed third so the state of Florida has several big cities with high levels of accidents. Los angeles ranks second which is still high. It is possible to infer that the number of accidents in California is spread out across several cities since it is the states with the highest number of accidents. Texas is the third state in regards to the number of accidents and two of its cities, Dallas and Houston are in the top 5 cities with the highest number of accidents.
The proportion of cities with high level of accidents is very low. It represents 4.25% of total cities. This means that less than 5 cities out of 100 cities have more than 1000 accidents per year. This could imply that there are few cities with extremely high numbers of accidents among the numerous cities in the US.

Time

The majority of accidents happen between 3pm and 6pm. This period of time represents rush hours. This might be the reason why there are more accidents at those specific times as the traffic is denser, with people trying to get home after work. Most accidents also seem to happen during the weekdays which corroborates the assumption that accidents are higher when workers are on the road, going to work or coming back from work. 
Additionally, accidents appear to be more frequent in December. This is an interesting fact because December is a month with several holidays and celebrations (Christmas, New Year's Eve) and a lot of people take some time off at this time of the year. However, there also a lot more traffic especially around the holidays. This underlines that higher traffic may be a big factor when it comes to accidents happening in the US.

Weather

There seems to be more accidents when the weather is mild. The highest number of accidents is seen when the temperature is between 64F and 72F. One explanation for this may be that there are more people going out when the weather is mild or warm than when it is cold, rainy or snowy. Deeper analysis would be useful to confirm this assumption. 

In conclusion, higher traffic seems to be a common factor when it comes to high number of accidents. It would be insightful to do further analysis on this topic by adding a dataset on population and traffic in the US. The goal would be to determine what is the relation between high traffic and populated areas and the number of accidents in the US.

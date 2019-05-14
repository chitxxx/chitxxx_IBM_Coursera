# chitxxx_IBM_Coursera

## Introduction
Walking down the streets in London, it is not difficult to spot that despite the prosperity of the metropolis, it is one of the city where homelessness is most pervasive.  One of the reason contributing to the phenomenon is due to the relative ease to beg for money, because of the streams of tourist London welcome every year. For an urnban planning point of view, it is important to understand the underlying factors of the homeless' behavior and pattern when selecting a neighborhood to setle in. In this project, we would attempt to identify the distrubution of homeless in different borough in London. Extending from that, we seek to investigate whether there is an correlation between number of McDonald's to the number of homeless in a borough, as it is known that many homeless do treat McDonald's as a shelter, given the fast food chain's relative tolerance to them at nights.

## Data

The two data that will be used in the project will be <br/>
1. Homelessness Provision, Borough, London Datastore (https://data.london.gov.uk/dataset/homelessness) <br/>
2. Foursquare API <br/>
The government data of homeless statistics gives us the numebr of homeless people compare with the overall popullation across differnet borough in London. By that, we can calculate the ratio of homeless people in each of the borough and identify the level of homelessness in each borough. We can then convert the location of each borough into coordinates in order to prepare for the search on on the Foursquare API. By using the API, we can count the number of Venues, in this case McDonald's in within a set radius of the location to estimate the number of venues within the borough. From that we can analysis whether there is a relationship between homelessness and no. of McDonald's.

![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/report_1.JPG "impage")
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/report_2.JPG "impage")
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/report_3.JPG "impage")

## Homelessness Across London
By doing a basic analysis on the data, we can spot that the level of homeless people across different different borough significantly vary. It is as expected that more posperous neighborhood such as Kensignton have a lower level of homelessness, while it is clear that City of London is a outlier, possibly due to special registration policies of the borough.

The data is then used to generate a hitmap to reflect the physical distrubution of homeless. See as follows, 
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/map_h.JPG "impage")

## Number of McDonald's
Using the same list of borough, the foursquare api is then used to find the number of McDonald's in eac borough. The radius parameter is set to 1500m to find a reasonable estimation. The same heatmap is then generate to compare if any correlation exist between no. of McDonald's and level of homelessness.
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/report_4.JPG "impage")
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/map_m.JPG "impage")

## Conclusion 
From the data generated, it is seen that little correlation exist between the number of McDonald's and homeless people. It is more clearly shown in the bar chart below.
![alt text](https://github.com/chitxxx/chitxxx_IBM_Coursera/raw/master/report_5.JPG "impage")

## Dissusion
Although it is shown that limited correlation exist between number of McDonald's and homeless from the limited analysis conducted. There exist few major limitations of the study, firstly being that the foursquare api only give a rough estimation of the borough bondaries, with a ciruclar shape having 1500m radius. This lead to inaccuracy when counting number of McDonald's hence inaccuracy in the analysis. Above that, it is known that homeless people are rather mobile and frequently locate themselves away from where they are registered, combined with the inaccuracy in the government data because of difficulties to track homeless, the no. of homeless is also not entirely accurate. Nonetheless, it is interesting to further investigate in what is the main factors behind homeless' location. 

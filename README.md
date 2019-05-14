# chitxxx_IBM_Coursera

## Introduction
Walking down the streets in London, it is not difficult to spot that despite the prosperity of the metropolis, it is one of the city where homelessness is most pervasive.  One of the reason contributing to the phenomenon is due to the relative ease to beg for money, because of the streams of tourist London welcome every year. For an urnban planning point of view, it is important to understand the underlying factors of the homeless' behavior and pattern when selecting a neighborhood to setle in. In this project, we would attempt to identify the distrubution of homeless in different borough in London. Extending from that, we seek to investigate whether there is an correlation between number of McDonald's to the number of homeless in a borough, as it is known that many homeless do treat McDonald's as a shelter, given the fast food chain's relative tolerance to them at nights.

## Data

The two data that will be used in the project will be <br/>
1. Homelessness Provision, Borough, London Datastore (https://data.london.gov.uk/dataset/homelessness) <br/>
2. Foursquare API <br/>
The government data of homeless statistics gives us the numebr of homeless people compare with the overall popullation across differnet borough in London. By that, we can calculate the ratio of homeless people in each of the borough and identify the level of homelessness in each borough. We can then convert the location of each borough into coordinates in order to prepare for the search on on the Foursquare API. By using the API, we can count the number of Venues, in this case McDonald's in within a set radius of the location to estimate the number of venues within the borough. From that we can analysis whether there is a relationship between homelessness and no. of McDonald's.


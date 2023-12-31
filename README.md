# Final-Project-Statistical-Modelling-with-Python
In this project, I examine the locations and capacities of the Bixi bike-share system in Toronto, ON. I compare this data to data from Yelp and Foursquare, looking for points of interest (POIs) around each bike station. My goal is to determine if there is a relation between the number and types of POIs around each station and the bike capacity of that station. I attempt to build a statistical model of the relationship.

## Project/Goals
I extracted data about each bike station from the City Bike API. Specifically, I obtained information such as the station location, name, and the total number of bike slots available.

Subsequently, I analyzed the categories available from the Yelp and Foursquare APIs to identify the types of Points of Interest (POIs) that were likely to impact bike traffic. Based on my analysis, I selected categories of drink and dining which are situated in Toronto, Ontario and I only found 669 stations in Toronto.
Using the Foursquare and Yelp APIs, I retrieved data for these POIs within a 1000-meter radius of each bike station. After retrieving the data, I performed data cleaning to remove duplicates. 
For every bike station, I calculated the total count for each category as well as the overall count across all types. To facilitate understanding and analysis, I generated graphical representations of this data. Additionally, I developed a statistical model.

The data sources I utilized for this analysis include: https://citybik.es/,
https://location.foursquare.com/developer/reference/places-api-overview, 
https://fusion.yelp.com/

## Results
In my selected area, there were only five bike stations available, which provided me with limited data to analyze. To compensate for the scarcity of information, I decided to collect the number of restaurants(drink and dine) and points of interest (POIs) within a 1000-meter radius of each station. However, the data revealed that the number of restaurants(drink and dine) or POIs did not appear to have any significant impact, if any at all, on the availability of bikes or the number of empty slots for bikes at the stations.


## Challenges 
I believe that the extremely small size of the dataset posed additional challenges when it came to the modelling stage. Unless I am overlooking something, it is evident that the available data was insufficient for comprehensive analysis and modelling.

## Future Goals
To take this project, the data would need to be cleaned more to eliminate near matches, and categories should be broken down to give further detail. Other factors that could be considered include a bike station's proximity to other bike stations and the population density around each station. frankly, I tried to add more categories but when I started to run it just show me the first category I added. 

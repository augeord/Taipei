# Housing Sales Prices & Venues Data Analysis of Taipei City
## A. Introduction
### A.1. Description & Discussion of the Background
Taipei is the 40th most-populous urban area in the world—roughly one-third of Taiwanese citizens live in the metro district.  Taipei city is home to an estimated population of **2,646,204** (2019). Taipei City is divided up into 12 administrative districts. I have been living in Taipei city for 10 years and had good experience there, then I decided to use Taipei City in my project. Taipei City is an enclave of the municipality of New Taipei City that limits cover an area of **271.7997** square kilometers [1].     

Taipei is a densely populated urban areas which continued to increase from year to year as well as the surrounding cities. Taipei is one of the world’s most expensive cities and crowded which make it harder for investors to do business around the city, unaffordability remains a serious issue. Most investors would prefer to have access to relevant information to invest in their preferable district at a lower real estate cost and the type of business that is more popular in this area. Obviously, most people are looking for lower price real estate value and less dense area as well. It is difficult for investor to get this information in one place.        

All these problems give an opportunity to create a map and information chart with real estate index marked in Taipei city and each district depending of the venue density.      
### A.2. Data Description
To provide a possible solution you will need data listed below:
*  I used **Foursquare API** to get the most common venues of given District of Taipei City [2].
*  I found the Second-level Administrative Divisions of the Taipei City from Spatial Data Repository of NYU [3]. The .json file has coordinates of the all city of Taiwan. I cleaned the data and reduced it to city of Taipei [(Here is my .json file)]( https://github.com/augeord/Taipei/blob/master/map.geojson) where I used it to create choropleth map of Housing Sales Price Index of Taipei.
*  I used **Google Map**, ‘Search Nearby’ option to get the center coordinates of each District. [4].
*  I collected latest per square meter Housing Sales Price (HSP) Averages for each District of Taipei from housing retail web page [5] [(Here is my datas)](https://github.com/augeord/Taipei/blob/master/Data.csv)
#### References:
* [1]  [Taipei_Wikipedia](https://en.wikipedia.org/wiki/Taipei)
* [2]  [Forsquare API](https://developer.foursquare.com/) 
* [3] [Second-level Administration Division of Taiwan](https://geo.nyu.edu/catalog/stanford-fn648mm8787) 
* [4]  [Google map](https://www.google.com/maps/)
* [5]  [Housing Sales Prices of each District from "Century21global” for 2020"](https://www.century21global.com/taiwan) 

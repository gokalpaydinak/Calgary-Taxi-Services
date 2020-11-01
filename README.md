# Calgary-Taxi-Services
Calgary Taxi Services study to define the best areas for establishing the branches

# Business Case:
Calgary Private Taxi Service

# Introduction:
An Investing company requested a study to define best place or places to establish a Taxi service Company in Calgary. They are requesting to define hotspots in the area and related venues where a customer can reach their service easily and in the meantime there will be connection between the branches so that all the caps\Taxis do not need to return back all the time back to their original location.

# Data Science Strategy:
Initially, following data will be collected for defining highly populated areas, business areas, industrial areas and hot spots such as Universities, libraries:
•	Calgary Community Census Data, which shows population and house quantity in each neighbourhood \ district in Calgary.
•	 Calgary Services Data, which shows all the hotspots such as universities, libraries, hospitals, businesses, industrial areas, etc.
After cleaning the data and parsing other related information from the websites, several folium maps will be prepared to visualize high population, business, and attractive areas. 

# Data Sources:
•	https://data.calgary.ca/Demographics/Census-by-Community-2019/rkfr-buzb
•	https://data.calgary.ca/Services-and-Amenities/Community-Services-Map/qeyz-gjec
•	https://en.wikipedia.org/wiki/Category:Universities_and_colleges_in_Calgary

# Foursquare Data:
Foursquare API will help me to collect nearest attractive places around hot spots such as coffee shops, pubs, pharmacies, restaurants, stores, etc. 

# Clustering:
After clustering all these data along with the Foursquare API generated json data, it will further show us areas to open “Taxi Service Company” branches and size of those branches.

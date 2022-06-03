# World_Weather_Analysis

## Purpose 
The purpose of this project is to make a few changes to the "PlanMyTrip" app, where the users can see a weather description and use personalized weather preferences to narrow down potential travel destinations and nearby hotels. 

## Results: 

### 1st Deliverable 
API call on the OpenWeatherMap was used to retrieve the following data: 
- Latitude and Longitude
- Maximum Temperature
- Percent Humidity
- Percent cloudiness
- Wind speed
- Weather description (ex - overcast, fog, light rain, clear sky)

The above weather data was added to a DataFrame and then exported to a CSV file named "WeatherPy_Database" that can be found in the "Weather_Database" folder. 

### 2nd Deliverable 
Input statements were written so that the customer can input their preferences for minimum and maximum temperatures. A hotel name was then retrieved based on the destinations with the preferred temperature requirements.  A new DataFrame was created where any destinations retrieved that did not have a hotel were dropped. This DataFrame was exported to a CSV file named "WeatherPy_vacation" and saved in the "Vacation_Search" folder.  A marker layer map was then created to visualize the destinations cities.  The map, titled "WeatherPy_vacation_map" is saved in the "Vacation_Search" folder  and it includes a pop-up marker for each city displaying the following information: 
- Hotel Name
- City
- Country
- Current weather description

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/103215123/171900284-a91b3641-cb34-4d74-8ca1-5103f481c1b0.png)

### 3rd Deliverable 
Based on the inputs from the customer, four destination cites were chosen as part of an itinerary, and a DataFrame was created for each city.  After retrieving the latitude and longitude pairs for each of the four cities, a directions layer map showing a potential round trip travel route among the four destinations was created. The directions layer map can be found in the "Vacation_Itinerary" folder and is named WeatherPy_travel_map.  Another pop-up marker layer map was also created, titled "WeatherPy_travel_map_markers".  The pop-up markers provides the customer with hotel, City, Country, and current weather descriptions along with maximum temperature.  

![WeatherPy_travel_map](https://user-images.githubusercontent.com/103215123/171901857-2855fc93-1634-468f-b925-86b8dbae3cd3.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/103215123/171901889-1247b591-2d77-454f-9b2b-5958b7dad30a.png)




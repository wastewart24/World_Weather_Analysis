# World_Weather_Analysis
A client wants to enhance an app that helps plan vacation trips to include a weather database that identifies and filters over 700 cities around the world based on factors like temperature, humidity, and wind speed using OpenWeatherMap API. The app will then create a vacation itinerary to show the travel route between the cities with a markery layer map using Google Maps API.

### Weather Database
The database was created using 2,000 random latitudes and longitudes to retrieve the nearest city and filtering out locations with no nearby cities. The API then retrieved the current weather description for each city. Lastly, a dataframe was created to organize the cities.

### Vacation Search
In order to retrieve customer weather and location preferences, input statements were implemented to identify temperature constraints for potential locations. Those inputs would filter and identify potential destinations and nearby hotels. Then, those destinations would appear on a marker layer map with pop-up markers. 
<img width="1207" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/43667985/203854519-9c0c5be7-6b01-4725-b800-aa8d28172712.png">

### Vacation Itinerary
An itinerary was created using the Google Directions API that shows the route between the four selected cities from the user's input. A marker layer map would then be created with a pop-up marker for each city.
<img width="927" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/43667985/203854635-e0d57f23-72d8-4636-872c-7d90d42692e6.png">
<img width="923" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/43667985/203854641-d1bcc57e-602e-4040-989f-9d7b54e1ffc9.png">

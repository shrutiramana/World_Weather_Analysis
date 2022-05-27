# World_Weather_Analysis - The main purpose of PlanMyTrip is to collect and analyse weather data for various cities worldwide.So that they can recommend ideal hotels and plan a itierinary for 4 cities to visit as per the client's weather preferences.

## Resources

##Data Source - Starter codes for the deliverables. Software - Python 3.8.5, Jupiter Notebook 6.1.4

# Summary
## Deliverable 1 - Retrieve Weather Data 

This involved gathering following data for about 2000 cities across northern and southern hemisphere -
1. City
2. Country
3. Lat
4. Lng
5. Max Temp
6. Humidity
7. Cloudiness
8. Wind Speed
9. Current Description.
Once we get the data , we form a Dataframe using Pandas and export the data into a csv file.

<img width="792" alt="Screen Shot 2022-05-27 at 1 57 28 PM" src="https://user-images.githubusercontent.com/98556229/170773722-71ec8889-6a72-467c-a408-201343c33bc0.png">


## Deliverable 2 - Create a Customer Travel Destinations Map
1. Based on the desired temperature requirements as provided by the Client/user.
2. We create a new dataframe fo rthe preferred cities to visit. 
3. We retrieve Hotel Names nearby search. 
4. We export this data as CSV file.
5. Using google API we create a marker layer map to show 
    - Hotel Name
    - City
    - Country
    - Current Weather description and maximum temperature.
 
<img width="723" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/98556229/170774397-7b39dfc7-0cd1-4b59-8067-31323f9ad3b4.png">

## Deliverable 3 - Create a Travel Itinerary Map
1. We use Google Directions API
2. Create 4 dataframe for each city. 
3. We retrieve latitiude and longitude for each city and store it in a tuple.
4. A directions layer map is created for the 4 citites selected.

<img width="727" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/98556229/170774858-57c586ff-0d95-434f-8795-2f9e102061c5.png">


5. A marker layer map with a pop-up marker is created for all the 4 cities.

<img width="721" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/98556229/170774864-7ba28ace-88ab-41ff-a74a-1da8961f7188.png">




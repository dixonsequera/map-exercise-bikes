![image](https://github.com/TheBridge-FullStackDeveloper/map-exercise-LA-metro/assets/33903092/51876334-cc02-4c8d-b840-c6355c85046f)

# Map-Exercise 🗺️

In this challenge, students will use OpenFreeMap with the MapLibre library to visualize bike-sharing stations in Madrid using the [CityBik API](https://citybik.es/). 

## Tasks 📝

After initializing the map in `index.js`, you should:

### Set Up a Global Map View:
- Configure the map for a global view centering it on Madrid. 

### Fetch Bike Networks from CityBik:
- Use the endpoint `https://api.citybik.es/v2/networks/bicimad` to retrieve all available bike-sharing networks in Madrid city.

### Display Bike Stations with Markers:
- For each network retrieved, add a marker on the map at the coordinates of each station.

### Button to Center on User’s Location:
- Add a button that centers the map on the user’s location using the `https://api.techniknews.net/ipgeo/` API.

## Bonus 🏆

### Customize Marker Icons by Availability:
- Change the color of the markers based on bike availability (e.g., green for high availability, yellow for medium, red for low or no availability) Check if the API gives this information already.

### Add Informative Popups:
- When clicking a marker, show a popup with the station’s name, address, the number of available bikes, and the number of available bike slots.

### Toggle Markers On/Off:
- Add a button to toggle markers: if they are visible, clicking the button hides them, and if they are hidden, clicking the button shows them again.

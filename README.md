![image](https://github.com/TheBridge-FullStackDeveloper/map-exercise-LA-metro/assets/33903092/51876334-cc02-4c8d-b840-c6355c85046f)

# Map-Exercise 🗺️

In this challenge, students will use OpenFreeMap with the MapLibre library to visualize bike-sharing stations worldwide in real-time using the [CityBik API](https://citybik.es/). 

## Tasks 📝

After initializing the map in `index.js`, students should:

### Set Up a Global Map View:
- Configure the map for a global view without centering on any specific city.

### Fetch Bike Networks from CityBik:
- Use the endpoint `https://api.citybik.es/v2/networks` to retrieve all available bike-sharing networks worldwide.

### Display Bike Stations with Markers:
- For each network retrieved, add a marker on the map at the coordinates of each station.

### Button to Center on User’s Location:
- Add a button that centers the map on the user’s location using the `https://api.techniknews.net/ipgeo/` API.

## Bonus 🏆

### Customize Marker Icons :
- Change the markers for an icon of a bike (choose the one you like).

### Add Informative Popups:
- When clicking a marker, show a popup with the station’s name and the company information.

### Toggle Markers On/Off:
- Add a button to toggle markers: if they are visible, clicking the button hides them, and if they are hidden, clicking the button shows them again.

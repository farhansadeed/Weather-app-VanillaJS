# Weather-app-VanillaJS

![Weather-app-VanillaJS](https://socialify.git.ci/farhansadeed/Weather-app-VanillaJS/image?language=1&owner=1&name=1&stargazers=1&theme=Light)

This is a weather app created by using HTML, CSS and VanillaJS. 
The app allows users to search for the current weather conditions and six-day forecast for any location. 

# This JavaScript file contains various functions used in a weather app built using Vanilla JS, HTML, and CSS (Sassy CSS). 
The functions handle tasks such as setting the placeholder text for the search bar based on screen size, 
displaying error messages, adding a spinner animation to a button, updating the display with weather information, 
and creating and displaying divs for the current weather conditions and six-day forecast.

- The file also contains helper functions for manipulating and formatting weather data, 
such as translating weather icons to FontAwesome icons, converting temperature and wind speed units, and building screen reader weather descriptions.

- This file can be included in a larger weather app project and used as a module to handle various UI and 
data manipulation tasks. The functions are organized and named in a clear and understandable way, making it easy to navigate and modify as needed.

The CurrentLocation class represents the current location and has properties for the 
name, latitude, longitude, and unit of measurement. It also has methods for getting and setting these properties and toggling the unit of measurement.
- setLocationObject is a function that takes a locationObj and a coordsObj as arguments, 
extracts the latitude, longitude, name, and unit of measurement from the coordsObj, 
and sets them as properties on the locationObj. 
If the unit of measurement is provided, it sets it as well.
- getHomeLocation is a function that retrieves the default weather location from local storage.
- getWeatherFromCoords is an asynchronous function that takes a locationObj as an argument, 
retrieves the weather data for the coordinates of the location, and returns the resulting JSON data. 
It does this by constructing a URL using the latitude, longitude, and unit of measurement properties 
of the locationObj and calling the OpenWeather API. However, this code is commented out and instead 
it calls an asynchronous function that posts to a Netlify function to retrieve the weather data instead.
- getCoordsFromApi is an asynchronous function that takes a entryText and units as arguments, 
retrieves the coordinates of the location from the OpenWeather API, and returns the resulting JSON data. 
It does this by constructing a URL using the entryText and units and calling the OpenWeather API. 
However, this code is also commented out and instead it calls an asynchronous function that posts to a Netlify function to retrieve the location data instead.

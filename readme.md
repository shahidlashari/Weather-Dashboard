Weather Dashboard

URL Links:
https://shahidlashari.github.io/HW6/

https://github.com/shahidlashari/HW6

Description:

The purpose of this assignment was to create a Weather dashboard application with search functionality to find current weather conditions and the future weather outlook for multiple cities using [OpenWeather.org] (https://openweathermap.org/). This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery. Used the [Moment.js](https://momentjs.com/) library to work with date and time.

The aim was If a traveler wants to see the weather outlook for multiple cities so that he can plan a trip accordingly.

Used AJAX to hook into the API to retrieve data in JSON format. The app runs in the browser and features dynamically updated HTML and CSS powered by jQuery. Displays the following under current weather conditions:

.City
.Date
.Icon image (visual representation of weather conditions)
.Temperature
.Humidity
.Wind speed
.UV index

It includes a search history so that users can access their past search terms. Clicking on the city name should performs a new search that returns current and future conditions for that city having 5-Day Forecast.

The weather dashboard has done through HTML, CSS, JQuery and openweather API. It utilizes Bootstrap with its components and utilities. There is also momentjs.com library to get date and time functions. The css file contains standard css practices , whereas the jQuery file contains variables functions like AJAX. JSON.parse and JSON.stringify function is used to get the stored data from local storage and set the data to local storage.

Technologies:

.HTML
.CSS 
.JQuery
.Bootstrap
.moment.js
.openweather API

Challenges:

This activity was a bit harder to use Ajax function and retrieve date from openweather API.I started my pseudo-code to work with . I went through lecture videos and also looking through a couple of examples online in order to understand jQuery code and Ajax function. During testing process my API key was temporary blocked due to the continual sufficient exceeding of the calls per minute limit by performing 581 requests within a minute but the limit for the Free account was 60 rpm. I used another account to get the key.
Application loads last searched city forecast on page load.

Bonus
It uses Geolocation API to add the user's current location to the initial landing page.

![image](https://user-images.githubusercontent.com/61823648/78966718-6f1c0d00-7ab5-11ea-9c9c-eba5eb7025e8.png)

# WeatherProgram
a program to input a city / state combination like "Syracuse, NY" Then outputs the weather forecast at that location

we use two different web APIs: 

Google's geolocation API takes a location and returns back JSON data containing the global position of that location (latitude and longitude). We will use the request.json() method function to decode the json result from the API into a Python object.

The second API is a weather forecaster courtesy of darksky.net. This API required a set of coordinates (latitude and longitude) and returns back JSON data containing the current weather conditions and the 7 day forecast.

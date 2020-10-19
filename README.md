#### Installation
1. kopiere js/config.tpl.js zu js/config.js
2. setze in config.js den Wert für die Konstante API_KEY:
Benutze hier Deinen openWeatherMap-API-Key den Du bei der Registrierung
dort erhalten hast.

Siehe: https://home.openweathermap.org/

````
const API_KEY = "your key here",
	apiURL = "http://api.openweathermap.org/data/2.5/weather?lat=%LAT%&lon=%LNG%&lang=de&units=metric&APPID=" + API_KEY,
	iconURL = "http://openweathermap.org/img/w/%ICON%.png",
	initLat = 54.4,
	initLng = 14.0,
	initZoom = 8
;
```` 

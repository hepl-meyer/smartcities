
Le but de ce code est d'aller rechercher la météo sur openweathermap à partir d'un code python en utilisant la librairie requests?

Grace au site https://jsonformatter.curiousconcept.com/# il est possible de modifier la reponse en json fournie par le code de manière à la rendre plus lisible.
Résultats de base:
{'coord': {'lon': 5.5675, 'lat': 50.6337}, 'weather': [{'id': 800, 'main': 'Clear', 'description': 'clear sky', 'icon': '01d'}], 'base': 'stations', 'main': {'temp': 22.37, 'feels_like': 21.71, 'temp_min': 20.56, 'temp_max': 22.72, 'pressure': 1014, 'humidity': 40}, 'visibility': 10000, 'wind': {'speed': 3.6, 'deg': 170}, 'clouds': {'all': 0}, 'dt': 1683223592, 'sys': {'type': 1, 'id': 1249, 'country': 'BE', 'sunrise': 1683173253, 'sunset': 1683226886}, 'timezone': 7200, 'id': 2792413, 'name': 'Liège', 'cod': 200}
Résultats transformé:

{
   "coord":{
      "lon":5.5675,
      "lat":50.6337
   },
   "weather":[
      {
         "id":800,
         "main":"Clear",
         "description":"clear sky",
         "icon":"01d"
      }
   ],
   "base":"stations",
   "main":{
      "temp":22.37,
      "feels_like":21.71,
      "temp_min":20.56,
      "temp_max":22.72,
      "pressure":1014,
      "humidity":40
   },
   "visibility":10000,
   "wind":{
      "speed":3.6,
      "deg":170
   },
   "clouds":{
      "all":0
   },
   "dt":1683223592,
   "sys":{
      "type":1,
      "id":1249,
      "country":"BE",
      "sunrise":1683173253,
      "sunset":1683226886
   },
   "timezone":7200,
   "id":2792413,
   "name":"Liège",
   "cod":200
}

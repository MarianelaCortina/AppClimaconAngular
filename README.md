WeatherApp está realizada con Angular 13, siguiendo el tutorial de DominiCode. 

Cuando ingreses a la app, te pedirá permiso para conocer tu ubicación, así te podrá mostrar el clima de tu ciudad en tiempo real.
Esto está logrado gracias al uso de geo-localicación, a través del uso de la API OpenWeatherMap (https://api.openweathermap.org). 
Cuando le das permiso, toma las coordenadas de la ciudad donde te encuentras, se las envía a la API y esta te devuelve la respuesta cargando la temperatura en la app.

También podrás buscar la temperatura de la ciudad que escribas en el buscador. 
Esto se logra gracias al uso de la API OpenWeatherMap, la cual es llamada desde la app, y trae como respuesta la temperatura, 
el clima (nublado, soleado, etc) que se muestra con un ícono, la presión, la humedad, como respuesta al  nombre de la ciudad que escribiste en el input.

Además, agregué el botón "Clear" para borrar el input y refrescar la página automáticamente, así podrás seguir buscando el clima de más ciudades.

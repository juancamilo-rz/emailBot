# emailBot

Envío de publicidad personalizada y análisis de datos:

* Identifica las zonas frecuentes desde las que un usuario accede al servicio y personaliza los anuncios que son enviados a su e-mail según las zonas visitadas.

* Procesa datos y genera gráficas estadisticas con métricas de interés para conocer el consumo de publicidad.

*Desarrollador por Juan Camilo Reyes Zuñiga - IA (UDC, 2017-II).*

## Definición de zonas

* [Zona 1](zona-1.png) - Cartagena 
  * Área definida: latitud entre 10.31 y 10.47, longitud entre -75.60 y -75.50.
  * Publicidad: BMW, Mazda, Land Rover, Mercedes-Benz.
  
* [Zona 2](zona-2.png) - Medellín 
  * Área definida: latitud entre 6.16 y 6.32, longitud entre -75.64 y -75.51.
  * Publicidad: Mercedes-Benz, Mazda, Audi, Porsche.

* [Zona 3](zona-3.png) - Barranquilla 
  * Área definida: latitud entre 10.88 y 11.06, longitud entre -74.88 y -74.72.
  * Publicidad: Porsche, Toyota, BMW, Ford.
  
* [Zona 4](zona-4.png) - Bogotá
  * Área definida: latitud entre 4.37 y 4.86, longitud entre -74.32 y -73.95.
  * Publicidad: Audi, BMW, Mercedes-Benz, Ford.
  
* [Zona 5](zona-5.png) - Cali
  * Área definida: latitud entre 3.27 y 3.51, longitud entre -76.60 y -76.42.
  * Publicidad: Porsche, Mazda, Audi, Toyota.
  
## Desarrollado con

* [MongoDB](https://www.mongodb.com/) - Base de datos
* [Node.js](https://nodejs.org/) - Lenguaje lado servidor
  * [Express](https://expressjs.com/) - Framework para Node.js
  * [Mongoose](http://mongoosejs.com/) - Usado para gestión de BD
  * [Geoip-lite](https://github.com/bluesmoon/node-geoip) - Usado para geolocalización
  * [Nodemailer](https://nodemailer.com/about/) - Usado para gestión de correos

## Licencia

Este proyecto está licenciado bajo Apache 2.0 - ver el archivo [LICENSE](LICENSE) para más detalles

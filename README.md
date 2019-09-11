# demoSwagger
Resumen/ proceso de desarrollo

## Dominio: 
- Especificar el dominio.

## Instalación de Swagger:

 '$ npm install -g swagger'
 
 '$ swagger — version
  0.7.5'
  
 '$ swagger project create nombreproyectoapi'
 
 - Escoger el framework express 
 - En la carpeta api se implementa toda la lógica de la aplicación.
 - config
 
 ## Arranque:
 
 '$ swagger project start -m
Starting: /home/nat/workspace/proyectos/carpetaDemo/nombreproyectoapi/app.js...
  project started here: http://localhost:10010/
  project will restart on changes.
  to restart at any time, enter `rs`
try this:
curl http://127.0.0.1:10010/hello?name=Scott'

- Usar la opción -m para que levante swagger a modo de mock de forma automática, lo que permite probar el API sin necesidad de escribir una sola línea de código en Node.

- Escribir y ver respuesta:
  'http://127.0.0.1:10010/hello?name=Scott'

# Entonces...
-- Swagger construye una api: se puede en el fichero.yml o fichero.json

#### Datos sacados de https://medium.com/@diegopm2000/creando-un-api-rest-con-swagger-node-c880bdac04a5


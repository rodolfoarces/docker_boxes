# Laravel

La aplicación laravel se basa en el uso de un archivo de configuración **.env**, en el mismo se declara el nombre de la aplicación, así como los parámetros de conexión a la base de datos.

El primero paso es crear la imagen de base con los componentes y herramientas necesarias

```
docker-compose -f laravel-standalone.yml build
```

Luego se inicia el contenedor basado en la imagen previamente creada

```
docker-compose -f laravel-standalone.yml up -d
```

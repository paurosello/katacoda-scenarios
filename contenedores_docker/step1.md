# Comandos gestion de contenedores

## Mostrar los contenedores descargadas en el servidor
Para ver las contenedores en ejecucion ejecutamos ``docker container ls``{{execute}}

Para ver todos los contenedore ``docker container ls -a``{{execute}}

## Crear un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container create lherrera/cowsay``{{execute}}

## Ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container start``{{copy}} *identificador_contenedor* o *nombre_contenedor*

## Eliminar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container rm alpine``{{execute}}

## Crear y ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker run alpine``{{execute}}
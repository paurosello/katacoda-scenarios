# Comandos basicos

## Mostrar los contenedores descargadas en el servidor
Para ver las contenedores en ejecucion ejecutamos ``docker container ls``{{execute}}

Para ver todos los contenedore ``docker container ls -a``{{execute}}

## Crear un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container create lherrera/cowsay``{{execute}}

## Ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container start``{{copy}} *identificador_contenedor* o *nombre_contenedor*

Para saber el *identificador_contenedor* o *nombre_contenedor* usa el comando ``docker container ls -a``{{execute}}. Con los primeros 3-4 caracteres del identificador es suficiente.

## Ver logs de un contenedor 
Para ver los logs de un contenedor ``docker container logs``{{copy}} *identificador_contenedor* o *nombre_contenedor*

## Eliminar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container rm alpine``{{execute}}

## Crear y ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker run alpine``{{execute}}
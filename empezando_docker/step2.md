# Arquitectura
![Arquitectura Docker](https://docs.docker.com/engine/images/architecture.svg)

# Servidor Docker
Ejecutaremos los primeros comandos al servidor de Docker. (Docker Daemon)

## Mostrar contenedores ejecutandose
Podemos listar los contenedores ejecutandose mediante ``docker ps``{{execute}}

## Nuestro primer contenedor
Podemos listar los contenedores ejecutandose mediante ``docker run hello-world``{{execute}}

## Mostrar todos los contenedores
Si queremos ver los contenedores que estan parados o terminados ``docker ps -a``{{execute}}

Si el codigo del `STATUS` es 0, el contenedor se ha ejecutado correctamente.

## Mostrar las imagenes locales
Para ver las imagenes que hay disponibles en el servidor ``docker images``{{execute}}
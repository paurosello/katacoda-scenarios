# Arquitectura
![Arquitectura Docker](https://docs.docker.com/engine/images/architecture.svg)

# Servidor Docker
Ejecutaremos los primeros comandos al servidor de Docker. (Docker Daemon)

## Mostrar contenedores ejecutandose
Podemos listar los contenedores ejecutandose mediante ``docker ps``{{execute}}

## Nuestro primer contenedor
Podemos listar los contenedores ejecutandose mediante ``docker run hello-world``{{execute}}

Que ha ocurrido el ejecutar este comando?:
```
To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.
```

## Mostrar todos los contenedores
Si queremos ver los contenedores que estan parados o terminados ``docker ps -a``{{execute}}

Si el codigo del `STATUS` es 0, el contenedor se ha ejecutado correctamente.

## Mostrar las imagenes locales
Para ver las imagenes que hay disponibles en el servidor ``docker images``{{execute}}
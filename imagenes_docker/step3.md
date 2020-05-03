
# Crear imagen de un contenedor

## Arrancamos un contenedor de forma interactiva
``docker run -it --name=container_test ubuntu /bin/bash``{{execute}}

## Creatmos un fichero dentro del contenedor y salimos con Control+D
``echo "hello" > new_file.txt``{{execute}}

## Listamos los contenedors creados
``docker container ls --all``{{execute}}

## Le indicamos a docker que cree una imagen de un contenedor parado
``docker commit container_test image_from_container:latest``{{execute}}

## Comprobamos que se ha creado la imagen
``docker image ls``{{execute}}

## Ejecutamos un contenedor con la imagen que acabamos de crear
``docker run -it --rm image_from_container /bin/bash``{{execute}}
# Comandos basicos

## Mostrar las imagenes descargadas en el servidor
Para ver las imagenes en ejecucion ejecutamos ``docker image ls``{{execute}}

## Buscar imagenes en registry
Para buscar imagenes en ``docker search wordpress``{{execute}}

## Descargar imagen registry por defecto
Descargar la imagen al servidor de docker ``docker pull wordpress``{{execute}}

Descargar especificando registro completo ``docker pull docker.io/nginx``{{execute}}

## Descargar imagen Quay
Descargar especificando registro Quay ``docker pull quay.io/bitnami/elasticsearch``{{execute}}

## Descargar tag especifica
Descargar especificando tag ``docker pull wordpress:php7.2``{{execute}}
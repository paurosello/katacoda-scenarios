# Construir imagenes

## Situare en la carpeta del primer ejemplo
``cd ~/example1``{{execute}}

## Construir imagen
``docker build .``{{execute}}

## Ejecutar imagen
``docker run <id>``{{copy}}

## Construir imagen con nombre
``docker build . -t example1``{{execute}}

## Ejecutar imagen con nombre
``docker run example1``{{execute}}

## Modifica el mensaje dentro del fichero Dockerfile
Cambia `Hello World Image` por `Hello 1.0.0`

## Construir imagen con tag
``docker build . -t example1:1.0.0``{{execute}}

## Anadir tag a una imagen existente
``docker tag example1:1.0.0 example1:dev``{{execute}}

## Ejecutar imagen con tag
``docker run example1:1.0.0``{{execute}}
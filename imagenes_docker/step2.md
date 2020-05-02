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
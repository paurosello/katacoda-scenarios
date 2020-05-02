
# Comandos dentro del contenedor

## Ejecutar un comando al arrancar el contenedor
Todo lo que especifiquemos detras del nombre de la imagen es un comando que ejecutamos dentro del contenedor : ``docker run -i --rm alpine echo "Hello World"``{{execute}}

## Abrir una terminal dentro del contenedor
Hay que habilitiar la interactividad y el [tty](https://en.wikipedia.org/wiki/Tty_(unix)) : ``docker run -i -t --rm alpine /bin/sh``{{execute}}

Ejecuta el comando ``hostname``{{execute}} y te devolvera el identificador del pod.

Para salir de la linea de comandos usa `Control+D`
# Comandos basicos

## Modo interactivo
Para poder ver la salida de un comando podemos arrancar un conetenedor de forma interactiva con ``docker container start --interactive <id>``{{copy}}

Formato corto: ``docker container start -i <id>``{{copy}}

## Borrar contedor al terminar
Si queremos borrar un contendor al finalizar la ejecucion ``docker container run --rm lherrera/cowsay``{{execute}}

Comprobad que despues de ejecutar el comando no se deja ningun contenedor creado.

## Arrancar en segundo plano
Podemos arrancar un contenedor en segundo plano mediante ``docker container run -d lherrera/cowsay``{{execute}}

Simplemente nos devolvera el identificador con el cual podremos comprobar los logs o realizar acciones adicionales.

## Arrancar en segundo plano y borrar
Se pueden mezclar las opciones: ``docker container run --rm -d lherrera/cowsay``{{execute}}
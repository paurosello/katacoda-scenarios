# Comandos basicos

## Modo interactivo
Para poder ver la salida de un comando podemos arrancar un conetenedor de forma interactiva con ``docker container start --interactive <id>``{{copy}}

Formato corto: ``docker container start -i <id>``{{copy}}

## Borrar contedor al terminar
Si queremos borrar un contendor al finalizar la ejecucion ``docker container run --rm lherrera/cowsay``{{execute}}

# Comandos dentro del contenedor

## Ejecutar un comando al arrancar el contenedor
Para ver los detalles de un contenedor arrancamos un contenedor en segundo plano: ``docker run --name=nginx_server nginx``{{execute}}

Despues podemos ver los detalles: ``docker container inspect nginx_server | jq``{{execute}}

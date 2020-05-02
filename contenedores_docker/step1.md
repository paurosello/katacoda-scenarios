# Comandos basicos

### Mostrar los contenedores descargadas en el servidor
Para ver las contenedores en ejecucion ejecutamos ``docker container ls``{{execute}}

Para ver todos los contenedore ``docker container ls -a``{{execute}}

### Crear un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container create lherrera/cowsay``{{execute}}

Al terminar la creacion de un contenedor nos devuelve el identificador que le ha asignado.

### Ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container start <id>``{{copy}}

Para saber el *identificador_contenedor* o *nombre_contenedor* usa el comando ``docker container ls -a``{{execute}}. Con los primeros 3-4 caracteres del identificador es suficiente.

### Ver logs de un contenedor 
Para ver los logs de un contenedor ``docker container logs <id>``{{copy}}

### Eliminar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker container rm <id>``{{copy}}

### Crear y ejecutar un contenedor
Para ver los volumenes que hay disponibles en el servidor ``docker run lherrera/cowsay``{{execute}}
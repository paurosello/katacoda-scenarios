
# Ver detalles de una imagen

## Construccion imagen 2 capas
Abre el archivo ``example2/Dockerfile`` y observa como anadimos un fichero dentro del contenedor

Construimos esta imagen con ``cd ~/example2 && docker build . -t example2``{{execute}}

Probamos a ejecutar la imagen ``docker run --rm example2``{{execute}}

## Detalles de una imagen
Para ver mas informacion de una imagen podemos ejecutar: ``docker image inspect example2 | jq``{{execute}}

## Herramienta visualizacion capas de una imagen
Para ver mas informacion de una imagen podemos usar la herramienta [Dive](https://github.com/wagoodman/dive)

Se instala mediante ``wget https://github.com/wagoodman/dive/releases/download/v0.9.2/dive_0.9.2_linux_amd64.deb && sudo apt-get update && sudo apt install ./dive_0.9.2_linux_amd64.deb``{{execute}}

Despues podemos explorar una imagen mediante ``dive example2``{{execute}}

- Pulsa la flecha hacia abajo para selecciona la segunda capa
- Pula el tabulador para moverte al panel de la derecha
- Pulsa Control+U para esconder los archivos no modificados
- Pula Control+C para salir
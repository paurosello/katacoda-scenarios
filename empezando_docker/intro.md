# Empezando con docker

La arquitectura docker se compone de los siguientes componentes:

![Arquitectura Docker](https://docs.docker.com/engine/images/architecture.svg)

- **Docker Daemon**: un proceso servidor que funciona en un segundo plano del sistema host y permite el control central del motor de Docker. Además se encarga de crear y administrar todas las imágenes, contenedores o redes.
- **Docker Client**: Herramienta que permite a los usuarios hablar con el servidor de Docker.
- **Docker Registry**: Donde se almacenan las imágenes.
- **Docker Objects**: Incluye las imágenes, redes, contenedores, volúmenes y plugins.
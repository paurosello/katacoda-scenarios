
# Publicar imagen en dockerhub

## Crea una cuenta en Dockerhub
Entra en [Dockerhub](https://hub.docker.com/) y crea una cuenta para poder subir tus imagenes.

## Crea un token de acceso a dockerhub
- Accede a [opciones de seguridad](https://hub.docker.com/settings/security)
- Crea un token de acceso con nombre `katacoda`
- Copia el token en un lugar seguro
- Ejecuta ``docker login --username <username>``{{copy}}
- Introduce el token
- Al acabar la sesion, elimina el token de tu cuenta

## Anadir tag con tu usuario a la imagen creada anteriormente
``docker tag example1:1.0.0 <username>/example1:dev``{{copy}}

## Subir imagen a dockerhub
``docker push <username>/example1:dev``{{copy}}

## Accede a tu imagen en dockerhub
- Abre la web `https://hub.docker.com/repository/docker/<username>/example1`
- Comprueba que el identificador de la imagen coincide con lo que tienes en tu terminal
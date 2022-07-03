# Docker

Automatiza el despliegue de aplicaciones dentro de contenedores de software, proporcionando una capa adicional de abstracción y automatización de virtualización de aplicaciones en múltiples sistemas operativos.

Los contenedores tendrán las dependencias de las aplicaciones esto permite que solo instalemos estas dependencias.

La principal diferencia contra las maquinas virtuales es que solo vamos a correr nuestra aplicación junto con los archivos que necesita nuestra aplicación.

El kernel que corre cada contenedor está compartido con el host, el host me da el kernel para compartir con las aplicaciones, es decir un contenedor linux corre en un serve que tenga server de linux, pasa lo mismo con windows, pero con docker desktop crea un kernel de linux que permite correr contenedores linux.

En resumen, docker correr un contenedor a partir de una imagen, esta imagen contiene:

- Sistema Operativo
- Software (apache y librerias)
- App

## Imagen

Es un archivo o file que se encuentra compuesto de diversas capas y que se utiliza con el objetivo de ejecutar un código dentro de un contenedor de Docker.

```bash
docker run image_name:tag
```

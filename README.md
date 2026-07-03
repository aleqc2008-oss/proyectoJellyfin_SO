# proyectoJellyfin_SO
Proyecto Jellyfin con Podman
Este repositorio contiene los archivos utilizados para el despliegue de Jellyfin utilizando Podman en Ubuntu y AWS EC2.

## Contenido
- Comandos de despliegue.
- Scripts utilizados durante la práctica.
- Evidencias (capturas de pantalla en PDF).
- Video de la demostración.

## Comandos principales
sudo apt install podman -y
podman pull docker.io/jellyfin/jellyfin
podman run -d --name jellyfin --cpus=1 --memory=1 -p 8096:8096 -v /home/ale_wiw/jellyfin-config:/config -v /home/ale_wiw/jellyfin-media:/media docker.io/jellyfin/jellyfin
podman ps
podman ps -a
etc...

## Integrantes
- Alejandra Quispe Caja
- Mathias Espinoza
- Han Carlos Hernandez Chuccden

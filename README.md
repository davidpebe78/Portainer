# Portainer
## WebUI Docker 

 Portainer es una herramienta que simplifica la gestión y el mantenimiento de contenedores Docker. Ayuda a agilizar los despliegues, simplifica las migraciones y permite monitorizar y resolver problemas de una manera rápida e intuitiva. Se controla a través de un interfaz web.

## Requisitos Previos

Instalar [Docker y Docker-compose](https://github.com/davidpebe78/Docker-Install)

## Instalacion
Para instalar Portainer en nuestro sistema, crearemos un contenedor Docker utilizando la herramienta Docker Compose. Creamos la carpeta donde guardaremos nuestros contenedores.
  
    $ mkdir docker
    $ cd /docker
    $ git clone https://github.com/davidpebe78/Portainer.git

    $ docker-compose up -d

WebUI: http://[IPmaquina]:9000

Con esto creamos usuario y contraseña admin; y a disfrutar.

FROM ubuntu:18.04 
#Así se crea un contenedor para el repositorio por visual 

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update -yq
RUN apt-get install -yq build-essential\
    python-dev \
    python3-minimal \
    python3-pip \
    python3-dev \
    python3-venv 

ENTRYPOINT bash

#en la carpeta donde esta el docker, se ejecuta en la consola docker build --tag=demo (esto es el nombre) .
#luego se ejecuta docker image ls

#luego ejecutar docker run --rm -it demo : esto es para que corra la maquina y para salir solo se da exit

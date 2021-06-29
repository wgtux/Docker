# Docker
DockerFile and DockerComposer

https://blog.rocketseat.com.br/dockerfile-principais-comandos-para-criar-a-receita-da-imagem/


COMANDOS DOCKER

1- Listando images

docker image ls

2- Listando contêineres

docker container ls

3- Iniciando e parando contêineres

docker container start ID_DO_CONTAINER
docker container stop ID_DO_CONTAINER

4- Executando um contêiner

docker run nome_da_imagem
docker run ubuntu #em primeiro plano
docker run -d ubuntu #em segundo plano

5- Obtendo informações do contêiner

docker inspect <nome_do_container>

6- Removendo um contêiner

docker container rm ID_DO_CONTAINER

7- Removendo uma imagem

docker image rmi ID_DA_IMAGEM

8 – Baixando imagem

docker pull ID_DA_IMAGEM
docker pull mariadb

9- Acessando shell do contêiner

docker run -it nome_da_imagem /bin/bash
docker run -it ubuntu /bin/bash

10- Criando uma imagem a partir de um Dockerfile

docker build <caminho_do_arquivo>

DOCKER COMPOSER
docker-compose up -d

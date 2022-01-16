# spring-boot-dockerfile

## Dockerfile1
$ docker build -t seungkyua/spring-boot-dockerfile:ubuntu -f Dockerfile1 .
$ docker image ls
$ docker run -d --name myapp -p 8080:8080 seungkyua/spring-boot-dockerfile:ubuntu
$ docker container ps | grep seungkyua
$ docker container exec -it myapp bash
$ docker container rm -f myapp
$ docker push seungkyua/spring-boot-dockerfile:ubuntu

## Dockerfile2
$ docker build -t seungkyua/spring-boot-dockerfile:alpine -f Dockerfile2 .
$ docker image ls | grep alpine
$ docker run -d --name myapp -p 8080:8080 seungkyua/spring-boot-dockerfile:alpine
$ docker container ps | grep myapp
$ docker container exec -it myapp bash
$ docker container rm -f myapp
$ docker push seungkyua/spring-boot-dockerfile:alpine

## Dockerfile3








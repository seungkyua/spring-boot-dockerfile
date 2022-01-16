# spring-boot-dockerfile

$ docker build -t seungkyua/myapp:ubuntu -f Dockerfile1 .

$ docker image ls

$ docker run -d --name myapp -p 8080:8080 seungkyua/myapp:ubuntu

$ docker container ps | grep seungkyua

$ docker container exec -it myapp bash

$ docker container rm -f myapp



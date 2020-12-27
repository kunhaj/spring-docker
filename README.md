##Build Docker Image

```
docker build -t kunhaj/spring-docker:latest .
```

##List Docker Image

```
docker images
```

REPOSITORY             TAG       IMAGE ID       CREATED          SIZE
kunhaj/spring-docker   latest    49e6ee1f7438   12 seconds ago   356MB

##Run

```
docker run -p 8080:8080 docker.io/kunhaj/spring-docker
```

##Check

http://localhost:8080/ -> Hello Docker World
# Docker flutter web app


## Build the docker image command
```
docker build -t <DOCKER NAME> .
```

## Run the docker image after success building image
```
docker run -d -p <PORT FOR DOCKER>:<THE EXPOSE PORT> <DOCKER NAME>
```

## List the dockers
```
docker ps -a
```

## List the images
```
docker images
```

## Stop docker
```
docker stop <CONTAINER ID>
```

## Remove docker
```
docker rm <CONTAINER ID>
```

## Remove image
```
docker image rm <IMAGE ID>
```

### [Docker basics: how to start and stop containers](https://eldermoraes.com/docker-basics-how-to-start-and-stop-containers/)

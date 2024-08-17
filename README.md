# Docker flutter web app


## Build the docker image command
```
docker build -t <DOCKER NAME> .
```

## Run the docker image after success building image
```
docker run -d -p <PORT FOR DOCKER>:<THE EXPOSE PORT> <DOCKER NAME>
```

## Start existing container
```
docker start <container-name/ID>
```

## List the docker containers
```
docker ps -a
```

## List the images
```
docker images
```

## Stop docker container
```
docker stop <CONTAINER ID>
```

## Remove docker containers
```
docker rm <CONTAINER ID>
```

## Remove image
```
docker image rm <IMAGE ID>
```

### [Docker](https://docs.docker.com/engine/reference/commandline/docker/)

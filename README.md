# DOCKER-ENV

 A collection of docker files for development environments

## Environments

### Java 8 and Angular `./java8-angular`

#### Resources

- Java 8
- Ant
- Maven
- NodeJS
- NPM
- Angular CLI

## Build & Run

### Building image

Into the environment directory, run:

`docker-compose build`

### Building container

Building a container mounting a host directory:

`docker run --name <container_name> -d -t -i -v <host_dir>:<container_dir> <image_name> /bin/bash`

### Running container

`docker start <container_name>`

### Coding

It's possible to open any container directory with [Visual Studio Code Remote Development](https://github.com/Microsoft/vscode-remote-release).

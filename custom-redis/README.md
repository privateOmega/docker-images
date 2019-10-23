# Custom-Redis

Redis with custom settings.

## Installation

Run [docker build](https://docs.docker.com/engine/reference/commandline/build/) command to build docker image.

```bash
docker build -t "custom-redis" .
```

Build docker container from previously build image by running the [docker run](https://docs.docker.com/engine/reference/commandline/run/) command.

```bash
docker run --name custom-redis -d -p 6379:6379 custom-redis
```

# Mendix Docker Extension
 
## Getting Started

You can try it now! [![Install RabbitMQ extension](https://img.shields.io/badge/-Install%20Mendix%20extension-white?logo=docker)](https://open.docker.com/extensions/marketplace?extensionId=yogendra0sharma/mendix-docker-extension&tag=0.0.1)

### Pre-requisite

- Docker Desktop 4.12

```shell
 go get github.com/yogendra0sharma/mendix-privatecloud-go-sdk

```

## 1. Clone the repository


```shell
 git clone https://github.com/Yogendra0Sharma/Mendix-Docker-Extension
```

## 2. Build the Extension

```shell
 make build-extension
```
#### If you run into error: Failed to solve with frontend dockerfile.v0: failed to create LLB definition
```
export DOCKER_BUILDKIT=0
export COMPOSE_DOCKER_CLI_BUILD=0
```


## 3. Install the Extension

```shell
 docker extension install <name-of-extension>
 ```


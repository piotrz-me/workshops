# Docker tips and tricks for developers

What is this presentation about ?
Not about production, not about deploying our product.

## Why use docker on your workstation ?

Isolation
__zdjecie szuflady__

## Use ready tools

### Postgresql

### VSCode

docker run -it -p 8080:8080 -v "$(pwd):/home/coder/project" codercom/code-server --auth none 


### Passing secrets to apps
aws

### Network modes
consul

### Debug network interfaces

using --net container:web-app  + dockerize tcpdump + wireshark localy ?


kali linux 
docker run -d -p 6080:6080 lukaszlach/kali-desktop:xfce


## Dockerizing your tools

### Dockerfile
#### Layers

##### Docker buildkit

export DOCKER_BUILDKIT=1


#### Docker image history
#### Dockerignore 

#### Scanners

docker run --rm -i hadolint/hadolint < Dockerfile

 scanner on build /after build  microscanner and trivy

#### CMD and ENTRYPOINT

## Fast use docker apps (Azure Container Instances)


## Cleaninig after work

### logs
add "log-opts": { "max-size": "10m", "max-file":"3"} to daemon.logs
add log-driver to local

### other logs drivers

### docker system prune

docker run -d --restart=unless-stopped --name cleanup -v /var/run/docker.sock:/var/run/docker.sock docker /bin/sh -c "while true; do docker system prune -f && date ; sleep 24h; done"

This doesn't clean by default:
* Running containers
* tagged images
* volumes


## tips for java

### memory
java - cpu and memery , heapsize https://youtu.be/RwtrLjh8_SU?t=2609



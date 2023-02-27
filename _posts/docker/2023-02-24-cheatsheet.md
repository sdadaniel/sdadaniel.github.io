---
title: "Docker CheatSheet"
categories: "docker"
---

---

layout: post
title: "Docker CheatSheet"

---

## docker image

###### `docker images`

list docker images

###### `docker images -q`

list docker images's ids only

###### `docker rmi ${image}`

delete docker image

###### `docker rmi $(docker images -q)`

delete all images

## docker container

###### `docker ps -a`

list of running container

###### `docker ps -q`

list docker containers's ids only

###### `docker rm ${container}`

delete container

###### `docker mi $(docker ps -q)`

delete all images

##### `docker container prune`

delete all unused containers

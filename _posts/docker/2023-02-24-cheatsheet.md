---
title: "Docker CheatSheet"
categories: "docker"
---

### Overview

자주쓰는 도커 명령어를 정리해보았습니다.

## docker image

| 표현식                           | 설명                          |
| -------------------------------- | ----------------------------- |
| `docker images`                  | list docker images            |
| `docker images -q`               | list docker images's ids only |
| `docker rmi $(image)`            | delete docker image           |
| `docker rmi $(docker images -q)` | delete all docker images      |

## docker container

| 표현식                      | 설명                          |
| --------------------------- | ----------------------------- |
| `docker ps -a`              | list of running container     |
| `docker ps -q`              | list docker images's ids only |
| `docker rm ${container}`    | delete container              |
| `docker mi $(docker ps -q)` | delete all container images   |
| `docker container prune`    | delete all unused containers  |

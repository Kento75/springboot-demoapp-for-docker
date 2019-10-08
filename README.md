# springboot-demoapp-for-docker

[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FKento75%2Fspringboot-demoapp-for-docker%2Fbadge%3Fref%3Dmaster&style=flat)](https://actions-badge.atrox.dev/Kento75/springboot-demoapp-for-docker/goto)

```
# jar作成
$ mvn package

# docker image 作成
$ docker build -t spring-boot-docker .

# docker container 作成
$ docker run -d -p 8080:8080 spring-boot-docker
```

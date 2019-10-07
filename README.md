# springboot-demoapp-for-docker

```
# jar作成
$ mvn package

# docker image 作成
$ docker build -t spring-boot-docker .

# docker container 作成
$ docker run -d -p 8080:8080 spring-boot-docker
```
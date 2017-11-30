# springboot-docker-demo
This project is implemented in Spring boot and deployed the build in docker environment. Created docker image for docker implementation.

# Docker #

https://indrabasak.github.io/what-is-docker/

### Docker file used in this application ###
```
FROM openjdk:8
ADD target/springbootdocker.jar springbootdocker.jar
EXPOSE 8085
ENTRYPOINT ["java","-jar", "springbootdocker.jar"]

```

# Keypoints to Remeber #

* Create the DockerFile in the root folder
* Docker Container should be installed on your machine and it should be up and running.

### Happy Coding ###

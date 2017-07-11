# Sentinella Spring Boot
![Oooola}](/images/image.png)
# Requirements
* [Docker](https://docs.docker.com/engine/installation/)

# Build image
Modify file build.gradle in option group by your own docker hub user.
``` bash
$ docker login
$ ./gradlew build buildDocker
```
# Docker RUN

``` bash
$ docker run -p 8080:8080 -t gloriapg/sentinella-spring-boot
```
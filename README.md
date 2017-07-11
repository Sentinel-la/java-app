# motherfucker-spring-boot-docker
![Oooola}](/images/image.png)
# Requirements
* [Docker](https://docs.docker.com/engine/installation/)

# Build image
``` bash
$ ./gradlew build buildDocker
```
# Docker RUN

``` bash
$ docker run -p 8080:8080 -t gloriapg/sentinella-spring-boot
```
# dockerfile-java

Alpine 3.5 -> Oracle Java 8u151

Lean Oracle Java8 Docker image based on `alpine:3.5`

Run the latest container with:

`docker run stakater/oracle-jdk:8u151-alpine-3.5`

`docker run stakater/oracle-jdk:8u151-alpine-3.5`

# Advanced

Build an image:
`docker build -t stakater/oracle-jdk:8u151-alpine-3.5 .`

Push an image:
`sudo docker push stakater/oracle-jdk:8u151-alpine-3.5`

_Note_ you might have to login first before you can push the image to docker-hub `sudo docker login`

# Example

`docker run -it --rm stakater/oracle-jdk:8u151-alpine-3.5 java -version`

# Reference

Copied from - `https://github.com/anapsix/docker-alpine-java`

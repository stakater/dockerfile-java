# docker-java

Lean Oracle Java8 Docker image based on `alpine:3.6`

Run the latest container with:

`docker run stakater/oracle-jdk:8u144-alpine-3.6`

# Advanced

Build an image:
`docker build -t stakater/oracle-jdk:8u144-alpine-3.6 .`

Push an image:
`sudo docker push stakater/oracle-jdk:8u144-alpine-3.6`

_Note_ you might have to login first before you can push the image to docker-hub `sudo docker login`

# Example

`docker run -it --rm stakater/stakater/oracle-jdk:8u144-alpine-3.6 java -version`

# Reference

Copied from - `https://github.com/anapsix/docker-alpine-java`
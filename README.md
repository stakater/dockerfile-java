# dockerfile-java

Alpine 3.5 -> Oracle Java 8u151

Lean Oracle Java8 Docker image based on `alpine:3.5`

Run the latest container with:

`docker run stakater/java8-alpine:latest`

`docker run stakater/java8-alpine:1.8.0_121`

# Advanced

Build an image:
`docker build -t stakater/java8-alpine .`

Push an image:
`sudo docker push stakater/java8-alpine`

_Note_ you might have to login first before you can push the image to docker-hub `sudo docker login`

# Example

`docker run -it --rm stakater/java8-alpine:1.8.0_121 java -version`

# Reference

Copied from - `https://github.com/anapsix/docker-alpine-java`

# java-spring-docker

This is a simple example of a Spring application that can be deployed using docker. 

## Build

To build this application: 

`mvn install dockerfile:build`

## Run 

To run the container: 

`docker run -p 8080:8080 luanrubensf/spring-docker`

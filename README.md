# Prerequisites
 * Docker installed
 * java 11
 * maven installed

# Docker images for Apache Kafka
 This repo provides build files for Apache Kafka and Confluent Docker images. The images can be found on Docker Hub, and sample Docker Compose files here.
 
## Docker Image reference
 Information on using the Docker images is available in the documentation,https://docs.confluent.io/platform/current/installation/docker/installation.html.

# Simple-spring-boot-kafka-project

## Build Project

Run the following command on the root project:

`mvn clean install`

## Start docker-compose

Run the following command on the root project:

`docker-compose up`

## Start spring boot application

Run the following command on the root project:

`docker-compose up`

## Run Spring boot application

# Notes

Confluent platform : _http://localhost:9021/_ 


Send a message to kafkaController to insert:

`curl --location --request POST 'http://localhost:8080/kafka/publish?message=dddd'`




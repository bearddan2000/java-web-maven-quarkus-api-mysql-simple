# java-web-maven-quarkus-api-mysql-simple

## Description
A POC for quarkus web api
connecting to a mysql database.

## Tech stack
- java
- maven
  - quarkus
  - hibernate
  - mysql connector
  - lombok

## Docker stack
- mariadb:latest
- maven:3-openjdk-17
- registry.access.redhat.com/ubi8/openjdk-11:1.11

## To run
`sudo ./install.sh -u`
curl -i localhost/dogs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

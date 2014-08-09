reated to run stagegage java services
FROM ubuntu
MAINTAINER scott_hendrickson

# We'll need maven to run spring boot
RUN apt-get update -y && apt-get install -y maven

# expose spring-boot default port
EXPOSE 8080

# the service home folder
RUN mkdir /usr/local/service

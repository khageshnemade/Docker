#1.First we need to decide to which os is going to used for our project
#2.Next we need to decide JDK/JRE to run 
#3.Then we need to feed the command to run java code
##Search on DockerHub website 
#i need ubuntu image
#FROM ubuntu
#FROM openjdk:11.0.16
FROM ubuntu
RUN apt update
#here -y is default choice when run below command
RUN apt install -y openjdk-17-jdk 
WORKDIR /myapp
COPY HelloWorld.class .
CMD java HelloWorld


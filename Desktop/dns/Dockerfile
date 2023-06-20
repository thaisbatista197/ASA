FROM ubuntu:latest

RUN apt update -y

RUN apt upgrade -y
 
RUN install bind9 bind9-utils dnsutils nano -y

RUN apt-get install dnsutils -y

RUN apt-get upgrade -y

EXPOSE 53

COPY ./etc/* /etc/bind

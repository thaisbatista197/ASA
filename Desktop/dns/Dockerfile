FROM ubuntu:latest

RUN apt-get update

RUN apt-get install bind9 -y

RUN apt-get install dnsutils -y

RUN apt-get upgrade -y

EXPOSE 53

COPY ./etc/* /etc/bind

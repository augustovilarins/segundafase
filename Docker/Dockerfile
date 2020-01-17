FROM ubuntu:latest

RUN apt-get update
RUN apt-get -y upgrade

RUN apt-get -y install apache2

EXPOSE 88
CMD apachectl -D FOREGROUND

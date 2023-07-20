FROM ubuntu:22.04 as base

RUN apt-get update && apt-get upgrade
RUN apt install openssl -y
RUN openssl version

RUN apt install bash

ENTRYPOINT ["tail", "-f", "/dev/null"]
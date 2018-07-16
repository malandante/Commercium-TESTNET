FROM debian:stretch
LABEL maintainer="Commercium Developers <dev@commercium.net>"
LABEL description="Dockerised CommerciumCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/

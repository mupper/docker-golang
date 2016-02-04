FROM golang:1.6-wheezy 

MAINTAINER leocomelli <leonardo.comelli@gmail.com>

RUN echo "deb http://http.debian.net/debian wheezy-backports main" >/etc/apt/sources.list.d/wheezy-backports.list \
    && apt-get update -qq \
    && apt-get -t wheezy-backports install -y -qq --no-install-recommends git \
    && go get -u github.com/gpmgo/gopm \
    && rm -rf /var/lib/apt/lists/*

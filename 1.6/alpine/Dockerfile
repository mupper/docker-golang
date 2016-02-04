FROM golang:1.6-alpine 

MAINTAINER leocomelli <leonardo.comelli@gmail.com>

RUN set -ex \
	&& apk add --no-cache --virtual git \
    && go get -u github.com/gpmgo/gopm

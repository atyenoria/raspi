# docker build -t node . && docker run -it node bash
FROM resin/rpi-node:4.0-slim-20151207
MAINTAINER atyenoria <eigotyoubunn30@gmail>

RUN mkdir /node-test
COPY ./test.js /node-test
WORKDIR /node-test

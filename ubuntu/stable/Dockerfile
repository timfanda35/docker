FROM ubuntu:14.04

MAINTAINER tsaikd "tsaikd@gmail.com"

ENV DOCKER_SRC /opt/docker/DOCKER_BASE/ubuntu-stable

ADD . $DOCKER_SRC

ENV HOME /root

RUN bash $DOCKER_SRC/build-all.sh

CMD bash $DOCKER_SRC/start-all.sh


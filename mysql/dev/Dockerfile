FROM DOCKER_BASE/mysql:phpmyadmin

MAINTAINER tsaikd "tsaikd@gmail.com"

ENV DOCKER_SRC /opt/docker/DOCKER_BASE/mysql-dev

EXPOSE 22
EXPOSE 80
EXPOSE 3306

ADD . $DOCKER_SRC

RUN bash $DOCKER_SRC/build-all.sh

CMD bash $DOCKER_SRC/start-all.sh


FROM java:latest
MAINTAINER Nepomuk Seiler
WORKDIR /opt/docker
ADD opt /opt
RUN ["chown", "-R", "daemon:daemon", "."]
USER daemon
ENTRYPOINT ["bin/akka-docker-cluster"]
CMD []

FROM ubuntu:16.04

MAINTAINER steven30801@gmail.com

USER root
WORKDIR /root

RUN apt-get update && \
    apt-get install -y curl

COPY onos-app _find-node _rest-port ./

RUN chmod +x onos-app

ENTRYPOINT ["./onos-app"]

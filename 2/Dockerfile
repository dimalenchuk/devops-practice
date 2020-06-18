FROM ubuntu:18.04

MAINTAINER dimalenchuk

RUN apt update -y
RUN apt install -y apache2

COPY lenchuk.yaml .

CMD service apache2 start

ENV university = "lsuls"
EXPOSE 8081

ENTRYPOINT tail -f /dev/null

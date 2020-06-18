FROM centos:latest

MAINTAINER dimalenchuk

RUN yum install -y epel-release
RUN yum install -y nginx

COPY lenchuk.yaml .

CMD top
EXPOSE 443

ENV MYSQL_DB = "CS21"

ENTRYPOINT tail -f /dev/null

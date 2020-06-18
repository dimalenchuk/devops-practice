FROM centos:7
MAINTAINER dimalenchuk

RUN yum -y update
RUN yum install -y java-1.8.0-openjdk

ADD lenchuk.sh .
CMD chmod 777 lenchuk.sh
CMD ./lenchuk.sh

EXPOSE 80

ENV GROUP = "21"

ENTRYPOINT tail -f /dev/null

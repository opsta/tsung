FROM ubuntu:18.04

MAINTAINER Jirayut Nimsaeng <jirayut@opsta.io>

RUN apt-get update && \
    apt-get install -y tsung

EXPOSE 8091

ENTRYPOINT ["tsung"]
FROM ubuntu:18.04

MAINTAINER Jirayut Nimsaeng <jirayut@opsta.io>

RUN apt-get update && \
    apt-get install -y tsung && \
    ln -s /usr/lib/x86_64-linux-gnu/tsung /usr/lib/tsung

EXPOSE 8090 8091

ENTRYPOINT ["tsung"]
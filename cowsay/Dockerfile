FROM debian:buster

MAINTAINER Jakub Matyszewski <jakubmatyszewski1@gmail.com>

RUN apt-get update && apt-get install -y cowsay fortune
VOLUME /data
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]

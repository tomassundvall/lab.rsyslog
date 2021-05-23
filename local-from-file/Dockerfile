FROM ubuntu:focal
RUN apt-get update && apt-get install rsyslog -y
WORKDIR /
CMD ["rsyslogd", "-n"]
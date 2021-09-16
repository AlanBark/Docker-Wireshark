FROM debian:latest
RUN apt update
RUN apt install -y tcpdump
WORKDIR /scripts
ENTRYPOINT ./tcpcapture.sh
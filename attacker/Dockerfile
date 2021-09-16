FROM kalilinux/kali-rolling
RUN apt-get update
RUN apt-get install -y hping3
WORKDIR /scripts
ENTRYPOINT ${SCRIPT_PATH}
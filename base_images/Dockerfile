FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive
RUN sed -i 's/archive.ubuntu.com/mirror.kakao.com/g' /etc/apt/sources.list
RUN apt update
RUN apt install -y ffmpeg python3 python3-pip
RUN pip3 install --upgrade youtube_dl
RUN apt-get clean

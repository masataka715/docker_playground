FROM ubuntu:16.04

RUN apt update && apt install -y binutils build-essential sysstat strace \
&& mkdir playground

WORKDIR /playground

RUN apt install -y python
FROM osrf/ubuntu_armhf:trusty

MAINTAINER Eduardo Feo eduardo@idsia.ch

USER root
ENV HOME /home/root

RUN apt-get update && apt-get install -y \
    build-essential \
    git \
    python-dev \
    python-pip

RUN pip install pyserial


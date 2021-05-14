#
# Ubuntu-20.04 Docker Container
#

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

# Install Dev tools
RUN apt-get update && apt-get install -y gcc make cmake tar g++ wget unzip git python2 cppcheck flex bison texlive-latex-extra doxygen graphviz
RUN apt-get install -y libreadline-dev libncurses5-dev libtinfo-dev libxml2-dev libz-dev libicu-dev liblzma-dev
RUN apt-get install -y pkg-config libgmp3-dev swig python2-dev

RUN apt-get install -y openssh-client

RUN mkdir ~/.ssh

#
# Ubuntu-20.04 Docker Container
#

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

# Install Dev tools
RUN apt-get update && apt-get install -y gcc make cmake tar g++ wget unzip git openjdk-8-jdk python2 python2-dev cppcheck flex bison texlive-latex-extra doxygen graphviz pkg-config 
RUN apt-get install -y libreadline-dev libncurses5-dev libtinfo-dev libxml2-dev libz-dev libicu-dev liblzma-dev libgmp3-dev swig

RUN apt-get install -y openssh-client
RUN mkdir ~/.ssh

#
# Ubuntu-20.04 Docker Container
#

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive

# Install Dev tools
RUN apt-get update && apt-get install -y gcc make cmake tar g++ libxml2-dev wget unzip git
RUN apt-get install -y python2

RUN apt-get install -y openssh-client

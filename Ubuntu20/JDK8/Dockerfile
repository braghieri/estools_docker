#
# Ubuntu-20.04 Docker Container
#

FROM ubuntu:20.04

ENV DEBIAN_FRONTEND noninteractive


# Install Dev tools
RUN apt-get update && apt-get install -y tar wget unzip git maven openssh-client python2
RUN rm -rf /usr/lib/jvm/java-11-openjdk-amd64
RUN apt-get install -y openjdk-8-jdk

RUN mkdir ~/.ssh && chmod 700 ~/.ssh
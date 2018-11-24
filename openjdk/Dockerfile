FROM ubuntu:16.04

RUN \
  apt-get update && \
  apt-get install openjdk-8-jre -y && \
  rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64/


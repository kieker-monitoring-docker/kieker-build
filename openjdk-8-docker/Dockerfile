FROM openjdk:8-jdk-slim

RUN apt-get update -qq && \
    apt-get install -y git sudo

RUN useradd -m docker && echo "docker:docker" | chpasswd && adduser docker sudo

USER docker
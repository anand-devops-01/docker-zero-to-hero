# Dockerfile Basics

A Dockerfile is a script used to create Docker images.

## Basic Structure

FROM ubuntu:latest
RUN apt update
RUN apt install -y curl
CMD ["bash"]
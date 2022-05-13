# syntax=docker/dockerfile:1

FROM python:3.8-slim-buster

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY . .

ENTRYPOINT ['python3']

CMD ['run.py']

# FROM ubuntu:22.04

# LABEL maintainer="wireframeng@gmail.com"

# RUN apt update && \
#     apt-get update -y && \
#     apt install -y python3-pip python3-dev python3.10-venv

# RUN python3 -m pip install --user --upgrade pip && \
#     python3 -m pip install --user virtualenv && \
#     python3 -m venv env

# WORKDIR /app  

# COPY requirements.txt requirements.txt

# RUN pip install -r requirements.txt

# COPY . .

# ENTRYPOINT ['python3']

# CMD ['run.py']


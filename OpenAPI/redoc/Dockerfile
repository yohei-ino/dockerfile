FROM node:latest
RUN apt -y update \
 && npm i -g npm \
 && npm i -g redoc-cli \
 && apt autoremove -y \
 && rm -rf /var/lib/apt/lists/*

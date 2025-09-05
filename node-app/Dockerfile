# Base image
FROM node:20.17.0-alpine3.19


# Copying the source code docker image
COPY index.js /home/app/index.js
COPY package.json /home/app/package.json
COPY package-lock.json /home/app/package-lock.json


WORKDIR /home/app

RUN npm install

# Base image
FROM node:20.17.0-alpine3.19

WORKDIR /home/app

# Copying the source code docker image
COPY package.json /home/app/package.json
COPY package-lock.json /home/app/package-lock.json

RUN npm install

COPY index.js index.js



CMD ["npm","run", "dev"]

# request docker-hub
FROM node:alpine
# in image: create folder /app
# build: copy build-folder-content to /app
COPY . /app
# runtime: cd to /app
WORKDIR /app
# runtime: command to run within the container
CMD node app.js 
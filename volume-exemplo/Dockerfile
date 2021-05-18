FROM node:latest
MAINTAINER Ivo Villa
env NODE_ENV=production
env PORT=3000
COPY . /var/www
workdir /var/www
RUN npm install
entrypoint npm start
expose $PORT
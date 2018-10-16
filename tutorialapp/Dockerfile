FROM node:carbon
MAINTAINER Jayden Jang

RUN mkdir -p /app

WORKDIR /app

ADD ./ /app

RUN npm install

ENV NODE_ENV=production

CMD node nodejs_tutorial_server.js
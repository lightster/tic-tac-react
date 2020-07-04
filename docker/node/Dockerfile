FROM node:14-alpine

RUN apk add --no-cache git \
    && npm install -g npm http-server

WORKDIR /app

CMD npm start
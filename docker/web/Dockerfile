FROM node:14.15.0-alpine

WORKDIR /app

RUN apk update && \
    apl add git && \
    npm install && \
    npm install -g npm && \
    npm install -g @vue/cli

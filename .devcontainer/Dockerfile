FROM node:20.18.1-alpine

RUN apk update && \
    apk add sudo vim curl

RUN addgroup -S coder && \
    adduser -S coder -G coder
USER coder
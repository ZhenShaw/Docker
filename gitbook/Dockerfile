FROM alpine

LABEL zhenshaw <zhenshaw@foxmail.com>

RUN apk add --no-cache nodejs \
    && apk add --no-cache npm \
    && npm install -g gitbook-cli \
    && gitbook -V

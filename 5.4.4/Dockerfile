FROM node:12.14.1-alpine3.11
LABEL maintainer="uhooi <the_uhooi@yahoo.co.jp>"

ARG VERSION="5.4.4"

RUN set -x && \
    npm install -g prh@${VERSION} && \
    npm cache clean --force

WORKDIR /work
ENTRYPOINT ["/usr/local/bin/prh"]


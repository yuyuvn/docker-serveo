FROM alpine:latest
LABEL maintainer="taichunmin@gmail.com"

RUN set -ex; \
  echo "http://dl-cdn.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories; \
  apk update && \
  apk add --no-cache \
    openssl=3.5.3-r1 \
    libssl3=3.5.3-r1 \
    openssl-dev=3.5.3-r1 \
    autossh

CMD ["/bin/sh"]

FROM alpine:latest
LABEL maintainer="taichunmin@gmail.com"

RUN set -ex; \
  echo "http://dl-cdn.alpinelinux.org/alpine/edge/community" >> /etc/apk/repositories; \
  apk add --no-cache openssl=3.5.0-r2 libssl3=3.5.0-r2 openssl-dev=3.5.0-r2 autossh

CMD ["/bin/sh"]

FROM alpine:3.6

RUN apk update && \
    sed -i -e 's/v3\.6/edge/g' /etc/apk/repositories && \
    apk upgrade --no-cache -f musl


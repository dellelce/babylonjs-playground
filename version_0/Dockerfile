FROM alpine:latest as base

RUN apk add --no-cache nginx && mkdir /run/nginx

COPY src /src
COPY nginx.conf  /etc/nginx/nginx.conf

CMD /usr/sbin/nginx

EXPOSE 8099

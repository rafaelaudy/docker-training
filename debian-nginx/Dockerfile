FROM debian:buster-slim

RUN apt-get update
RUN apt-get install nginx -y
RUN service nginx start

CMD service nginx start && nginx -g 'daemon off;'

FROM nginx:alpine

RUN rm /etc/nginx/conf.d/*

COPY proxy_no.conf /etc/nginx/conf.d/

COPY ./ssl /etc/nginx/ssl

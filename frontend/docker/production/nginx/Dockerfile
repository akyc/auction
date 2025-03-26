FROM nginx:1.17-alpine

COPY ./ddocker/production/nginx/conf.d /etc/nginx/conf.d

WORKDIR /app

COPY ./public ./public

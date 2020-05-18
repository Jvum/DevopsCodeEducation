FROM nginx:1.15.0-alpine

#Remove default file from nginx to configure php-fpm
RUN rm /etc/nginx/conf.d/default.conf

COPY ./nginx.conf /etc/nginx/conf.d
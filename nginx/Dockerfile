FROM nginx:latest
MAINTAINER localhost
RUN mkdir -p /var/www/html
WORKDIR /var/www/html
ADD ./nginx/ /etc/nginx/conf.d
ADD ./web/ /var/www/html
EXPOSE 80

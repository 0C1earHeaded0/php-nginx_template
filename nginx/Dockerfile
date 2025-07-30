FROM nginx:1.29

WORKDIR /var/www/html

COPY ./app /var/www/html
COPY ./nginx/nginx.conf /etc/nginx/conf.d/default.conf

RUN apt-get update && apt-get install vim -y
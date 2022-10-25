FROM wyveo/nginx-php-fpm:php74
EXPOSE 80
RUN mkdir -p /var/log/nginx/
RUN mkdir -p /var/www/
RUN chmod -R 777 /var/www/
RUN chmod -R 777 /var/log/nginx/
COPY ./default.conf /etc/nginx/conf.d/

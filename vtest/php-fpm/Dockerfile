FROM php:7.3

RUN apt-get update && \
    docker-php-ext-install pdo_mysql \
    apt-get install mysqld gd

CMD ["php-fpm"]

EXPOSE 9000
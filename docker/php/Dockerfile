FROM php:7.0.7-fpm

RUN apt-get update && \
    apt-get install -y libcurl4-openssl-dev && \
    docker-php-ext-install mysqli pdo pdo_mysql curl

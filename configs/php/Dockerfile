FROM php:7.2-fpm-alpine3.7
MAINTAINER leequix <leequix@yandex.com>

RUN docker-php-ext-install -j$(nproc) \
mysqli \
pdo \
pdo_mysql
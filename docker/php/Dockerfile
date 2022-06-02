FROM php:8.0-apache
RUN apt-get update \
  && apt-get install -y git unzip \
  && docker-php-ext-install pdo_mysql \
  && a2enmod rewrite
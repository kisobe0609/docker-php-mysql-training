FROM php:8.1-apache-bullseye
RUN docker-php-ext-install pdo_mysql
RUN apt update
RUN apt install -y default-mysql-client
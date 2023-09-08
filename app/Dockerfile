FROM php:8.2.10-apache
RUN apt update \
	&& docker-php-ext-install pdo_mysql
COPY src/ /var/www/html/

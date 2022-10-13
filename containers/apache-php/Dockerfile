FROM php:8.1-cli
RUN apt-get update && apt-get upgrade && apt-get install unzip
RUN curl -sS https://getcomposer.org/installer -o composer-setup.php \
    && php composer-setup.php --install-dir=/usr/local/bin --filename=composer

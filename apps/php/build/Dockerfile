FROM php:8.1-fpm-alpine

ADD https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/

RUN chmod +x /usr/local/bin/install-php-extensions && \
  install-php-extensions apcu bcmath bz2 ldap pdo_mysql pdo_pgsql exif smbclient intl imap pcntl soap gmagick gmp gd zip

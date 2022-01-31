FROM php:7.4-apache
COPY . /var/www/html/
RUN docker-php-ext-install mysqli
RUN cd /etc/apache2/mods-available && a2enmod rewrite && /etc/init.d/apache2 restart
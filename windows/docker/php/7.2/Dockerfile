FROM php:7.2-apache
COPY . /var/www/html/
RUN docker-php-ext-install mysqli
RUN cd /etc/apache2/mods-available
RUN a2enmod rewrite
RUN /etc/init.d/apache2 restart
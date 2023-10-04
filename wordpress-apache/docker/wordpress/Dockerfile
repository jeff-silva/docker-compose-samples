FROM wordpress:latest
WORKDIR /var/www/html/wp-content/plugins/sas-wp-plugin

RUN chown -R www-data:www-data /var/www/html
RUN apt-get update && apt-get install -y zip unzip && curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

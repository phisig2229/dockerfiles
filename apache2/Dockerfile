FROM ubuntu

MAINTAINER Tyler Stewart <phisig2229@gmail.com>

# Update the repository
RUN apt-get update

# Download and Install Apache2
RUN apt-get install -y apache2

# Setting up the Enviroment Variables
#ENV APACHE_RUN_USER www-data
#ENV APACHE_RUN_GROUP www-data
#ENV APACHE_LOG_DIR /var/log/apache2

# Set the Volume
VOLUME /var/www

# Set the port
EXPOSE 80

# Set the entry point for the apache
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

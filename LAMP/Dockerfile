FROM ubuntu:latest
MAINTAINER DIN
RUN apt-get update -y
RUN apt-get -qq -y install apache2 libapache2-mod-php5 php5
COPY index.html /var/www/html
EXPOSE 80
CMD apache2 -g 'daemon off;' 

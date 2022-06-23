FROM ubuntu
MAINTAINER Heena Bansal
RUN apt-get update && apt-get install -y apache2 && apt-get clean && rm -rf /var/lib/apt/lists/*
ADD /sample.html /var/www/html/
VOLUME /var/www/html
ENTRYPOINT apachectl -D FOREGROUND

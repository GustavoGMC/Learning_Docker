FROM ubuntu
MAINTAINER Gustavo <gustavo.gmc@live.com>

RUN apt update
RUN apt -y install tzdata apache2
RUN echo "Teste dockerfile apache2" > /var/www/html/teste.html

EXPOSE 80
CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]

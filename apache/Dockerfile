
FROM ubuntu:23.10

RUN apt-get update -y && \
  apt-get install -y apache2

CMD ["apachectl", "-D", "FOREGROUND"]

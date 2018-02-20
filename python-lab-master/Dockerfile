FROM ubuntu:16.04

MAINTAINER DevOps

RUN apt-get update

RUN apt-get install nginx -y

COPY index.html /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

#This image based on centos 7 and will start apache service in each container

FROM centos:latest
MAINTAINER Mark.Fieldhouse@mafitconsulting

RUN yum update -y
RUN yum install -y httpd net-tools

RUN echo "This is a custom index file from docker" > /var/www/html/index.html

EXPOSE 80

ENTRYPOINT apachectl "-DFOREGROUND"


#Docker file based on latest CentOS 7 image
FROM centos:latest
MAINTAINER Mark.Fieldhouse@mafitconsulting.co.uk

RUN echo "EXPORT 192.168.0.0/24" >> /etc/exports.list
RUN useradd -ms /bin/bash user
USER user


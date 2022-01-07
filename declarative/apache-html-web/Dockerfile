FROM centos
MAINTAINER pawanitzone.kumar@gmail.com


RUN yum update -y
RUN yum install httpd -y

COPY code/* /var/www/html/

EXPOSE 80

# start the httpd service
CMD ["-D","FOREGROUND"]
ENTRYPOINT ["/usr/sbin/httpd"]


FROM centos:7
RUN yum install httpd -y
RUN echo "Hello-World" > /var/www/html/index.html
CMD ["usr/sbin/httpd", "-D","FOREGROUND"]
EXPOSE 80


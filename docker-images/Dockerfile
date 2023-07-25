FROM centos:7

RUN yum install httpd -y && \
    yum clean all && \
    rm -rf /var/cache/yum

CMD ["apachectl", "-DFOREGROUND"]


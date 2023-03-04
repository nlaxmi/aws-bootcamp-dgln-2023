FROM centos:7
MAINTAINER dgln
RUN yum -y update && \
    yum -y install httpd && \
    yum clean all
COPY ./start.sh /
RUN chmod +x /start.sh
ENTRYPOINT ["/start.sh"]
CMD ["true", "batman", "superman"]
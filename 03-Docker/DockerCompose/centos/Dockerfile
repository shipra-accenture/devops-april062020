# Base Image
FROM centos:7

# Owner Image
MAINTAINER Shipra Bhardwaj <shipra.bhardwaj25@gmail.com>

# Update system
RUN yum update -y

# Install Apache Package
RUN yum install -y httpd


# Run Apache Service
CMD ["/usr/sbin/httpd -k start"]


FROM centos:8.1.1911
MAINTAINER F0080

COPY requirements.txt /opt
WORKDIR /opt
RUN yum install python2 -y \
    && yum install gcc -y \
    && yum install python2-devel -y \
    && pip2 install -r requirements.txt
CMD ["/bin/bash"]

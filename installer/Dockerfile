FROM centos:7

RUN curl -sL https://rpm.nodesource.com/setup_6.x | bash - && \
    yum -y install epel-release && \
    yum -y install ansible nodejs gettext gcc gcc-c++ make git bzip2 && \
    yum -y clean all && \
    rm -rf /root/.cache

VOLUME /build
WORKDIR /build
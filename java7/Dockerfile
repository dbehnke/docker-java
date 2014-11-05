FROM dbehnke/ol6:latest

RUN yum update -y && \
    yum install -y curl wget unzip java-1.7.0-openjdk java-1.7.0-openjdk_devel && \
    yum clean all && \
    rm -r -f /var/cache/* && \
    rm -r -f /tmp/*

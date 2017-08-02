FROM ubuntu:17.10
MAINTAINER Yasssri Ratnayake <yasassri@wso2.com>

ENV JAVA_PKG=server-jre-8u*-linux-x64.tar.gz \
    JAVA_HOME=/usr/java/jdk1.8.0_141

ADD $JAVA_PKG /usr/java/

ENV PATH="/usr/java/jdk1.8.0_141/bin:${PATH}"

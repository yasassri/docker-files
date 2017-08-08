FROM tomcat:8-alpine

MAINTAINER Yasssri Ratnayake <yasassri@wso2.com>
# Backend Server to test ballerina servicces
ADD RESTfulService.war /usr/local/tomcat/webapps

# Docker Entry Point
ENTRYPOINT ["/usr/local/tomcat/bin/catalina.sh","run"]

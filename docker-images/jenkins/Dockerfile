FROM jenkins/jenkins:lts-jdk11

# File Author / Maintainer
MAINTAINER Skyglass

# Install plugins
COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt

FROM rhel

ENV JAVA_VERSION 1.8.0
RUN yum -y update && yum install -y java-"${JAVA_VERSION}"-openjdk-devel && yum -y clean all

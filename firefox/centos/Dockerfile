FROM centos:latest

LABEL base.os="centos7"
LABEL maintainer="StuMueller <stumueller@gmail.com>"

RUN yum -y update && yum -y install firefox

RUN yum -y clean all

CMD /lib64/firefox/firefox

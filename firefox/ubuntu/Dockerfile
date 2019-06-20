##
# docker run -d \
# --name="firefox" \
# -e DISPLAY=$DISPLAY \
# -v /tmp/.X11-unix:/tmp/.X11-unix \
# stumueller/firefox
##

FROM ubuntu:latest

LABEL base.os="centos7"
LABEL maintainer="StuMueller <stumueller@gmail.com>"

RUN apt-get update && apt-get install -y firefox

CMD /usr/bin/firefox

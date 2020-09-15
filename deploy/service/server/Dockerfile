FROM centos:7

ADD bin/server /

RUN chmod 777 /server

ENV PARAMS=""

ENTRYPOINT ["sh","-c","/server $PARAMS"]
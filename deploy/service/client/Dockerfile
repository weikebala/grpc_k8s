FROM centos:7

ADD bin/client /

RUN chmod 777 /client

ENV PARAMS=""

ENTRYPOINT ["sh","-c","/client $PARAMS"]
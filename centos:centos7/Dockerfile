FROM buzzy/build-centos:centos7

RUN curl -O http://public.redjack.com/centos:centos7/buzzy-0.5.0-1.x86_64.rpm \
 && sudo yum -y install buzzy-*.rpm \
 && rm buzzy-*.rpm

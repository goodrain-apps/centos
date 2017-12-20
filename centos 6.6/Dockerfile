FROM centos:6.5

RUN ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime

RUN groupadd  -g 200 rain \
    && useradd -u 200 -g 200 rain
    
ADD ./CentOS-Base.repo /etc/yum.repos.d/CentOS-Base.repo


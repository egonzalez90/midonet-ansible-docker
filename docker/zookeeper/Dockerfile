FROM midonet-base

MAINTAINER Eduardo Gonzalez <dabarren@gmail.com>

RUN yum install -y \
        java-1.7.0-openjdk-headless \
        zookeeper \
        zkdump \
        nmap-ncat \
     && yum clean all

RUN mkdir -p /usr/java/default/bin/ /var/lib/zookeeper/data \
     && chown zookeeper:zookeeper /var/lib/zookeeper/data \
     && ln -s /usr/lib/jvm/jre-1.7.0-openjdk/bin/java /usr/java/default/bin/java

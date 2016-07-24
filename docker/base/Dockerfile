FROM centos:7

MAINTAINER Eduardo Gonzalez <dabarren@gmail.com>

COPY datastax.repo /etc/yum.repos.d/datastax.repo

COPY midonet.repo /etc/yum.repos.d/midonet.repo

RUN yum install -y \
        centos-release-openstack-mitaka \
     && yum clean all

FROM centos

RUN rpm -ivh http://yum.puppetlabs.com/puppetlabs-release-el-7.noarch.rpm
RUN yum -y install puppet

ENTRYPOINT [ "puppet" ]
CMD ["agent", "--verbose", "--no-daemonize", "--summarize" ]
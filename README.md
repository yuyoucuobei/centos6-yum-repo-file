# centos6-yum-repo-file

centos6 vault yum repo file 

CENTOS6 mirror is invalid from 20201130

There is a valid yum source from vault.centos.org

[COMMAND]

mv /etc/yum.repos.d/CentOS-Base.repo /etc/yum.repos.d/CentOS-Base.repo.bak

cp CentOS-Base.repo /etc/yum.repos.d

yum clean all

yum makecache

yum install some packet...


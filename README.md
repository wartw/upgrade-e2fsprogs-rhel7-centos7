# upgrade-e2fsprogs-rhel7-centos7
Bash for upgrade e2fsprogs on CentOS 7 &amp; RHEL7

Run:
```
yum install unzip -y && wget https://github.com/wartw/upgrade-e2fsprogs-rhel7-centos7/archive/refs/heads/patch-1.zip -N --no-check-certificate && unzip master.zip && cd upgrade-e2fsprogs-rhel7-centos7-master && bash e2fsprogs_upgrade_rhel7.sh && resize2fs
```

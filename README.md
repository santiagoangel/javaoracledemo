#Java Oracle demo
==============

Demo app for Java, Hibernate with Oracle 11g, PL-SQL, Spring, UNIX Shell,  UML &amp; HTML5/Javascript/CSS



##Running on RHEL6 or Fedora 19/20:

*Prerequisites

```
$ /usr/sbin/groupadd -r dba

$ /usr/sbin/useradd -r -M -g dba -d /u01/app/oracle -s /bin/bash oracle

$ yum -y install bc net-tools
```

*Edit /etc/hosts to reflect real hostname in /etc/hostname:
```
#/etc/hostname content:
myserver

```

```
#/etc/hosts content:
127.0.0.1   localhost localhost.localdomain localhost4 localhost4.localdomain4 myserver
```

*Install
```
$ yum localinstall Descargas/Disk1/oracle-xe-11.2.0-1.0.x86_64.rpm 

```

*Configure
```
$ /etc/init.d/oracle-xe configure

```


---
title: linux
author: ljk
date: '2022-10-16'
slug: []
categories:
  - ~
tags: []
description: ~
featured_image: ~
---
# 重启网卡
```
service network restart
```

# 重启环境变量
```
source 配置文件名 
```

# 关闭防火墙
```
systemctl stop firewalld
```

# 强制安装
```
rpm -ihv --force --nodeps  XXXX
```

# 解压文件
```
tar -zxvf xxxxxx
```

# 配置jdk环境变量
```
export JAVA_HOME=/地址
export CLASSPATH=.:$JAVA_HOME/rt.jar:$JAVA_HOME/tools.jar:$JAVA_HOME/dt.jar
export JRE_HOME=$JAVA_HOME/jre
export PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin
export PATH=$PATH:$JAVA_HOME/bin:$JRE_HOME/bin
```

# 常见配置文件
```
etc/hostname 主机名文件
etc/host  IP映射文件
etc/sysconfig/network-scripts/ 网络配置文件
etc/profile 环境变量
```


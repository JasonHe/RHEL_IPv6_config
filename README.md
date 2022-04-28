# RHEL_IPv6_config
RHEL系（CentOS/AlmaLinux/Rocky Linux.....）IPv6+DHCP配置文件
目前仅在甲骨文过（请确认网卡名称为eth0），其他云厂商不保证可用性，请使用如下命令获取IPv6+DHCP
```
yum install wget -y && wget -O /etc/sysconfig/network-scripts/ifcfg-eth0 https://github.com/JasonHe/RHEL_IPv6_config/raw/main/ifcfg-eth0 && nmcli c reload
```

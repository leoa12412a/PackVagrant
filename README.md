# 打包屬於自己的Vagrant

以下範例為打包centos stream 9

## Virtualbox設定

1.第一個網路配置必須為NAT(參考<a href="https://developer.hashicorp.com/vagrant/docs/providers/virtualbox/boxes">官網</a>)
2.必須安裝VirtualBox Guest Additions才能共享資料夾等等功能(參考<a href="https://www.tonystechanditblog.com/2021/04/virtualbox-guest-additions-centos.html">網站</a>)
```
dnf update
dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm
#dnf install gcc kernel-devel kernel-headers make bzip2 perl
```

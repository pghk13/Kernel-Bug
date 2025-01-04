# Kernel-Bug

## 当前bug进度
--> 优先处理6.13-rc4未报告


## 跳板机链接服务器vscode配置
Host HostMachine
  HostName 10.177.29.218
  User root

Host Hukun
  HostName 172.16.0.107
  User hk
  ProxyJump HostMachine 

## 在学校内网下先ssh到宿主机
1. ssh root@10.177.29.218
pwd:Puersai.168

## 在宿主机ssh到虚拟机
2. ssh hk@172.16.0.107
pwd:hukun

 

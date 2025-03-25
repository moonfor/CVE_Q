漏洞复现

nginx日志查看，未限制文件路径与后缀，可任意读取文件

可读取.ssh下的SSH 密钥对

![image-20250325110111893](后台RCE.assets/image-20250325110111893.png)

点击追踪读取文件

![image-20250325110247192](后台RCE.assets/image-20250325110247192.png)

![image-20250325110326510](后台RCE.assets/image-20250325110326510.png)

通过密钥进行ssh登录

![image-20250325110409668](后台RCE.assets/image-20250325110409668.png)
## X-ray_FreeBSD_service
***
## 将xray-core作为FreeBSD服务运行

用法：

下载并解压 [Xray-core](https://github.com/xtls/xray-core) 于 /bin/x-ray/ 目录

在 /etc/rc.d/ 中创建 xray 文件并写入文件中内容

在 /etc/rc.conf 末尾添加 xray_enable=YES

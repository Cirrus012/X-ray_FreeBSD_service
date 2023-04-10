## X-ray_FreeBSD_service
***
#### 将xray-core作为FreeBSD服务运行

##### 用法：  
* 下载并解压 [Xray-core](https://github.com/xtls/xray-core) 于`/bin/x-ray/`目录  
* 创建 `/etc/rc.d/xray`文件并写入本仓库文件中内容：[xray](https://github.com/Cirrus012/X-ray_FreeBSD_service/blob/main/xray)  
* 为`/etc/rc.d/xray`赋予执行权限:  
`chmod +x /etc/rc.d/xray`  
* 在`/etc/rc.conf`末尾添加`xray_enable=YES`  
* 配置文件为`/bin/x-ray/config.json`

##### 支持命令：  
`service xray start`  
`service xray stop`  
`service xray status`  

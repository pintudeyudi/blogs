## 在kubernetes集群中部署shawdowsocks
### Use kubernetes cluster to build a shawdowsocks server in docker


## 写在前面
使用kubernetes来部署ss的容器的方法其实和直接使用容器搭建ss原理是一样的，好处是可以使用现成的平台启动和部署容器，不必自己费心登录到虚拟机上敲命令了，一切在云平台供应商的界面上操作就可以了，本次搭建演示试用了华为云平台cce，具体操作步骤如下。


### 1. 登录云平台，注册实名认证充值等
华为云容器引擎，地址如下：
http://console.huaweicloud.com/cce2.0/

注意，登录后选择左上区域亚太-香港
![image](https://github.com/pintudeyudi/blogs/blob/master/testsnap.PNG)

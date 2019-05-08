Frp-Server
===========

frp服务端(frps)的一键安装脚本

因原脚本不能安装新版本，特意fork了脚本源码，修改安装脚本为指定frps版本(0.25.3).

与本人恩山帖子配套，欢迎下载使用。

《远程控制新三OpenWRT路由器之——Frp(0.25.3)(内网穿透)》

https://www.right.com.cn/forum/thread-537917-1-1.html

脚本适用平台：CentOS、Debian、Ubuntu。

Server
------

### Install

```Bash
    git clone https://github.com/maxlicheng/frps0.25.3-install-shell.git
    cd frps
    chmod 700 ./install-frps.sh
    ./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```


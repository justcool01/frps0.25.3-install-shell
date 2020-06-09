Frp-Server
===========

frp服务端(frps)的一键安装脚本


脚本适用平台：CentOS、Debian、Ubuntu。

Server
------

### Install

```Bash
    git clone https://github.com/justcool01/frps0.25.3-install-shell.git
    cd frps0.25.3-install-shell
    cd frps
    sudo chmod 700 ./install-frps.sh
    sudo ./install-frps.sh install
```

### UnInstall
```Bash
    sudo ./install-frps.sh uninstall
```
### Update
```Bash
    sudo ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```


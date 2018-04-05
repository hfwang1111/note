# Mint18.3环境配置

## 软件安装

* ## **可deb包安装类**

网易云音乐

chorme 

visual studio code


* ## **pycharm**

官网下载.tar.gz包解压,一般移到/usr/local/opt 目录下,执行解压包内  /bin/pycharm.sh即可运行pycharm.
 
此时每次打开pycharm都要执行.sh文件,为了方便打开有几种方法.


1. 可创建.desktop文件快速启动.
.desktop文件格式如下:

```
#!/usr/bin/env xdg-open
[Desktop Entry]
Name=Pycharm
Comment=Python IDE(2018.1)
Exec=/pycharm-community-2018.1/bin/pycharm.sh 
Icon=/pycharm-community-2018.1/bin/pycharm.png
Terminal=false
Type=Application
Categories=Development;
StartupNotify=true
NoDisplay=true
```
.desktop文件的存放路径为/usr/share/applications


2. 利用mint桌面可以方便的制作启动器,桌面右击有选项制作启动器,添加 pycharm.sh

3. 利用软链从终端打开(安全又炫酷):

``ln ~/.../pycharm.sh /usr/bin/pycharm``

* ## **pip**

``sudo apt-get install python-pip``

``sudo apt-get install python3-pip``
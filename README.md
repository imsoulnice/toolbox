# Toolbox
**Some useful tools**

## SpeedTest
**三网测速1.SuperSpeed 全面测速修复版. By UXH & ernisn & oooldking**
<https://www.infski.com/speedtest>
```
bash <(curl -Lso- https://www.infski.com/files/superspeed.sh)
```
**三网测速2** 
```
bash <(wget -qO- https://bench.im/hyperspeed)
```

## DD Scripts
1.MoeClub 萌咖InstallNET.sh
```
bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/MoeClub/Note/master/InstallNET.sh') -d 10 -v 64 -p "自定义root密码" -port "自定义ssh端口"
```
2.https://git.beta.gs/
```
安装重装系统的前提组件:
Debian/Ubuntu:
apt-get install -y xz-utils openssl gawk file wget screen && screen -S os

RedHat/CentOS:
yum install -y xz openssl gawk file glibc-common wget screen && screen -S os

如果出现异常，请刷新Mirrors缓存或更换镜像源。
RedHat/CentOS:
yum makecache && yum update -y
Debian/Ubuntu:
apt update -y && apt dist-upgrade -y


使用:
wget --no-check-certificate -O NewReinstall.sh https://git.io/newbetags && chmod a+x NewReinstall.sh && bash NewReinstall.sh

如为CN主机(部分主机商已不能使用)，可能出现报错或不能下载脚本的问题，可执行以下命令开始安装.
wget --no-check-certificate -O NewReinstall.sh https://cdn.jsdelivr.net/gh/fcurrk/reinstall@master/NewReinstall.sh && chmod a+x NewReinstall.sh && bash NewReinstall.sh
```
## Some Tricks
1. zip文件解压缩中文密码转码
```
unzip -P "$(echo -n 中文密码|iconv -f utf-8 -t gbk)"  filename.zip
或者
7z x -p"$(echo -n 中文密码|iconv -f utf-8 -t gbk)" filename.zip
```

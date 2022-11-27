# toolbox
Some useful tools 

## DD Scripts
1.https://git.beta.gs/
/~
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
~/

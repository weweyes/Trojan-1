Trojan一键安装脚本

curl -O https://raw.githubusercontent.com/atrandys/trojan/master/trojan_mult.sh && chmod +x trojan_mult.sh && ./trojan_mult.sh

bbr,bbr+,锐速加速工具安装

cd /usr/src && wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

######################################################################

1.安装 curl，若是有此环境，请跳过

-----Ubuntu/Debian 系统安装 Curl 方法-----

apt-get update -y && apt-get install curl -y

-----Centos 系统安装 Curl 方法-----

yum update -y && yum install curl -y                   

2.有些 VPS 需要安装 XZ 压缩工具

-----Debian/Ubuntu 安装 XZ 压缩工具命令-----

apt-get install xz-utils 

-----CentOS 安装 XZ 压缩工具-----

yum install xz     



3.密码修改

/usr/src/trojan/server.conf

4.重启Trojan

systemctl restart trojan

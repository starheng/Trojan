Trojan 一键安装脚本

====================================

Trojan 一键安装自动脚本

系统：centos7+/debian9+/ubuntu16.04+

网站：www.v2rayssr.com （已开启禁止国内访问）

脚本东拼西凑 需要感谢 秋水逸冰、Atrandys、V2ray官方等

Youtube：波仔分享

====================================

脚本安装命令

安装wget

yum -y install wget    ##ContOS Yum 安装 wget
apt-get install wget   ##Debian Ubuntu 安装 wget
脚本如下

wget -N --no-check-certificate -q -O trojan_install.sh "https://raw.githubusercontent.com/V2RaySSR/Trojan/master/trojan_install.sh" && chmod +x trojan_install.sh && bash trojan_install.sh

# [Oracle Cloud VPS CentOS 7 升级内核并开启官方原版BBR加速](https://github.com/yyaf/yyaf-blog/issues/6)

# 配置流程
## 升级内核
更新 yum
yum -y update
查看内核
uname -r
手动下载秋水 BBRPlus 版内核
wget https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/bbrplus/centos/7/kernel-4.14.129-bbrplus.rpm
手动安装内核
yum -y install kernel-4.14.129-bbrplus.rpm
更新引导
grub2-mkconfig -o /boot/grub2/grub.cfg
grub2-mkconfig -o /boot/efi/EFI/centos/grub.cfg
列出系统开机启动项
sudo awk -F\' '$1=="menuentry " {print i++ " : " $2}' /boot/efi/EFI/centos/grub.cfg
设置新版内核默认启动项
grub2-set-default 0
重启
reboot
## 开启 BBRPlus 及优化
秋水一键脚本,选择7开启BBRPlus加速.
再次./tcp.sh运行脚本,选择10优化并重启完成.
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
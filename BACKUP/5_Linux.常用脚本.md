# [Linux 常用脚本](https://github.com/yyaf/yyaf-blog/issues/5)

# 系统优化相关
重装系统（DD 脚本）
> 萌咖大佬的一键DD脚本 [Github](https://github.com/veip007/dd) 
```bash
##镜像文件在OneDrive
wget -N --no-check-certificate https://raw.githubusercontent.com/veip007/dd/master/dd-od.sh && chmod +x dd-od.sh && ./dd-od.sh
```
```bash
##镜像文件在GoogleDrive
wget -N --no-check-certificate https://raw.githubusercontent.com/veip007/dd/master/dd-gd.sh && chmod +x dd-gd.sh && ./dd-gd.sh
```
TCP 加速
```bash
wget -N --no-check-certificate "https://raw.githubusercontent.com/chiakge/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
```
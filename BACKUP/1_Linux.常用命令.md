# [Linux 常用命令](https://github.com/yyaf/yyaf-blog/issues/1)

## 1. 用户管理

```
adduser username    // 创建用户
apt install sudo    // 安装sudo
usermod -aG sudo username   // 将用户添加到sudo组

sudo deluser username   // 删除用户
sudo deluser --remove-home username // 删除用户的主目录和邮件后台处理程序
```
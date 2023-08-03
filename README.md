# 宝塔面板
## CentOS官方纯原版：
```
curl -sSO https://raw.githubusercontent.com/zhucaidan/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```
## CentOS官方纯原版备份：
```
wget -O install.sh http://f.cccyun.cc/bt/install_6.0.sh && bash install.sh
```
>### PS：以上两条代码都可以安装宝塔7.7.0官方原版镜像，任选其一进行安装即可！

## 屏蔽强制绑定手机
```
sed -i "s|bind_user == 'True'|bind_user == 'XXXX'|" 
/www/server/panel/BTPanel/static/js/index.js
```
### 直接删除宝塔强制绑定手机js文件
```
rm -f /www/server/panel/data/bind.pl
```
# 如需要额外开通宝塔会员服务请执行以下操作：
## 一键开心脚本：
```
curl -sSO https://raw.githubusercontent.com/ztkink/bthappy/main/one_key_happy.sh 
&& bash one_key_happy.sh
```
## 开心脚本备用：
```
curl -sSO https://cdn.cheshirex.com/uploads/sh/one_key_happy.sh && bash 
one_key_happy.sh
```
### 以上开心脚本任选其一即可一键开心

## 一键优化脚本
```
wget -O optimize.sh http://f.cccyun.cc/bt/optimize.sh && bash optimize.sh
```
## 宝塔面板 官方原版v7.7.0版本面板备份

## btpanel-v7.7.0-backup 官方原版v7.7.0版本面板备份

### Centos/Ubuntu/Debian安装命令 独立运行环境
```
curl -sSO https://raw.githubusercontent.com/zhucaidan/btpanel-v7.7.0/main/install/install_panel.sh && bash install_panel.sh
```
# 宝塔面板卸载命令
## 执行下面命令
```
wget http://download.bt.cn/install/bt-uninstall.sh
sh bt-uninstall.sh
```

> 1. 是只卸载面板
> 2. 是面板以及运行环境

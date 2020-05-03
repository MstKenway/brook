# Brook 端口转发 一键管理脚本
原 逗比 Brook 端口转发 一键管理脚本 修改版
增加对动态域名的支持，开启监控后自动更新域名IP

使用方法：
1.先安装依赖，centos：
```
sudo yum install -y bind-utils
sudo yum install -y wget
```

debian/ubuntu:
```
sudo apt-get install -y dnsutils 
sudo apt-get install -y wget
```

2.安装程序并运行
```
wget https://raw.githubusercontent.com/MstKenway/brook/master/brook-pf-mod.sh 
chmod +x brook-pf-mod.sh
./brook-pf-mod.sh
```
感谢大佬的脚本，仅提供使用方法说明

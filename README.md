# v2ray
v2ray官方安装教程
Centos 7

官方安装地址
bash <(curl -L -s https://install.direct/go.sh)

启动
sudo systemctl start v2ray

停止
sudo systemctl stop v2ray

重启
sudo systemctl restart v2ray

查看是否开启状态
sudo systemctl status v2ray

开启，开机启动
sudo systemctl enable v2ray

关闭开机启动
sudo systemctl disable v2ray

升级更新
sudo bash go.sh

安装
curl -fsSL "https://alist.nn.ci/v3.sh" | bash -s install

#更新
curl -fsSL "https://alist.nn.ci/v3.sh" | bash -s update

#卸载
curl -fsSL "https://alist.nn.ci/v3.sh" | bash -s uninstall

启动: systemctl start alist
关闭: systemctl stop alist
状态: systemctl status alist
重启: systemctl restart alist


先cd到alist所在目录:
cd /opt/alist
随机设置新密码:
./alist admin random
或者手动设置新密码:
./alist admin set NEW_PASSWORD

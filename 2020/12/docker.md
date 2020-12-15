**安装**
首先卸载旧版本
sudo apt-get remove docker docker-engine docker.io containerd runc
通过docker仓库下下载deb包
https://download.docker.com/linux/debian/dists/buster/

换源
/etc/docker/daemon.json
{
"registry-mirrors": ["https://docker.mirrors.ustc.edu.cn"]
}

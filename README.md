# Docker Discuz
docker + nginx + php + mariadb + DiscuzX3.4

#### 安裝 Docker
基本的安裝可以參考 [Docker 安裝筆記 - 以LNMP為例的應用](https://twrory.com/2018/12/12/docker-install/)  

#### 安裝 Docker Compose
在安裝好Docker 之後、我們可以開始安裝 Docker Compose, 首先我們需要先安裝 python-pip
```
sudo yum install -y epel-release
sudo yum install -y python-pip
```
接下來就可以安裝Docker Compose了
```
pip install docker-compose
```
需要的話將 Python 相關的套件更新一下讓 Docker Compose 能夠順利運行
```
yum upgrade python*
```
#### 接下來只需要幾個步驟
Step1. git clone https://github.com/roryamos/DockerDiscuz.git  
Step2. cd DockerDiscuz  
Step3. git clone https://gitee.com/ComsenzDiscuz/DiscuzX.git html/discuz  
Step4. ./restart.sh  


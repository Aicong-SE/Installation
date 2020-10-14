#### Ubuntu 安装

```shell
# 设置密钥
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE
or
wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -
# 添加typora的远程仓库
sudo add-apt-repository 'deb https://typora.io/linux ./'
#更新
sudo apt-get update
#安装
sudo apt-get install typora
```


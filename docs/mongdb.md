https://www.cnblogs.com/leinov/p/7341139.html
## 安装

## 环境变量
cd ~/
touch .bash_profile
open .bash_profile
**写入环境变量**

source .bash_profile
## 启动

mongod --dbpath data --logpath log/mongod.log --logappend

## 连接

mongo

## 关闭

ps -ef | grep mongo

sudo kill  74316(pid)

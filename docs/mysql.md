## 安装
1. http://www.mysql.com/downloads/

2. brew install mysql
## 启动
1. sudo /usr/local/mysql/support-files/mysql.server start
2. sudo /usr/local/mysql/support-files/mysql.server stop
3. sudo /usr/local/mysql/support-files/mysql.server restart

## 创建数据库
1. 进入mysql终端
/usr/local/MySQL/bin/mysql -u root -p

// mysql 命令以分号结尾
2. create database someDataBase;

3. show databases;

3. use someDataBase;

## 创建表
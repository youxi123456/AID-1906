



git 终于学完了，开心

需要使用MySQLclient，当前django不支持pymysql

# mysqlclien错误解决

## 问题描述:

报错信息:

![](images\报错3.png)

**错误原因:**

没有mysqlclient模块导致django无法连接mysqldb。

## 解决方案

**思路:**

安装mysqlclient

**操作步骤**：

命令行键入命令`sudo apt-get install default-libmysqlclient-dev`

安装完成后命令行输入`apt list | grep 'default-libmysqlclient-dev'`

![](images\查看default-libmysqlclient-dev.png)

命令行键入命令 sudo pip3 install mysqlclient

安装完成后命令行输入`pip3 list | grep 'mysqlclient'`

![](images\查看mysqlclient.png)


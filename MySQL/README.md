# MySQL

学习网址

- https://www.runoob.com/mysql/mysql-install.html

进入MySQL安装目录

```
cd C:\web\mysql-8.0.11\bin
```

初始化数据库

```
mysqld --initialize --console
```

generated for root@localhost: ItpJ>%q5mj1E

初始密码是 ItpJ>%q5mj1E

安装服务

```
mysqld install
```

启动服务

```
net start mysql
```

登录MySQL

```
mysql -h 主机名 -u 用户名 -p
```

- **-h** : 指定客户端所要登录的 MySQL 主机名, 登录本机(localhost 或 127.0.0.1)该参数可以省略;
- **-u** : 登录的用户名;
- **-p** : 告诉服务器将会使用一个密码来登录, 如果所要登录的用户名密码为空, 可以忽略此选项。

连接主机

```
mysql -u root -p
```

重置密码

```
mysql admin -u root password "123456";
```

重置密码

```
ALTER USER 'root'@'localhost' IDENTIFIED BY '123456';
```

## 客户端

mysql-workbench 软件

- https://www.mysql.com/products/workbench/
















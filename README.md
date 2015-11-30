查看数据库服务器/主机当前连接的IP地址，提供一个参数用来查询网络连接端口。

例如：

1、查看MySQL数据库服务器当前连接的客户端IP地址列表：

./database_client_ip.sh 3306

2、查看Redis服务器当前连接的客户端IP地址列表：

./database_client_ip.sh 6379

3、查看MySQL数据库服务器当前连接的主机IP地址列表：
./database_host_ip.sh 3306

4、查看Redis服务器当前连接的主机IP地址列表：
./database_host_ip.sh 6379

P.S：脚本自动创建和清除临时文件；可以用于其他网络连接端口IP的状态查询。

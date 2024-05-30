# MySQL
## MySQL的基础语句，在终端中打开，读取数据，数据概览：
C:\Users\19215>mysql -uroot -pSyh0729.   --从终端打开MySQL
create database bjpowernode;       --创建一个名为bjpowernode的数据库
use bjpowernode;     --使用这个数据库
source C:\Users\19215\Desktop\MySQLdocument\bjpowernode.sql     --把数据导入新的数据库，路径为数据所在路径
show tables；     --查看数据库中的表格
select * from dept；     --从数据库中的dept表格中选取所有表头
desc dept;     --查看表概述

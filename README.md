# MySQL
## MySQL的基础语句，在终端中打开，读取数据，数据概览：
C:\Users\19215>mysql -uroot -pSyh0729.   --从终端打开MySQL  
create database bjpowernode;       --创建一个名为bjpowernode的数据库  
use bjpowernode;     --使用这个数据库  
source C:\Users\19215\Desktop\MySQLdocument\bjpowernode.sql     --把数据导入新的数据库，路径为数据所在路径  
show tables；     --查看数据库中的表格  
select * from dept；     --从数据库中的dept表格中查询所有  
desc dept;     --查看表概述  

## DQL 简单查询和条件查询语句
select 字段名1 （as） 别名 ，字段名2 from 表名；（英文字符）   --带空格或中文别名可以用单引号双引号包括起来，字段名可以直接进行数学运算  
where 字段名 （between _ and _    
              in _  
              is null  
              not  
              like % 或 _ ）  

     

# MySQL
## MySQL的基础语句，在终端中打开，读取数据，数据概览：
* C:\Users\19215>mysql -uroot -pSyh0729.   --从终端打开MySQL  
* create database bjpowernode;       --创建一个名为bjpowernode的数据库  
* use bjpowernode;     --使用这个数据库  
* source C:\Users\19215\Desktop\MySQLdocument\bjpowernode.sql     --把数据导入新的数据库，路径为数据所在路径  
* show tables；     --查看数据库中的表格  
* select * from dept；     --从数据库中的dept表格中查询所有  
* desc dept;     --查看表概述  

## DQL 简单查询和条件查询语句
* select 字段名1 （as） 别名 ，字段名2 from 表名；（英文字符）   --带空格或中文别名可以用单引号双引号包括起来，字段名可以直接进行数学运算，函数运算  
select distinct （字段名1，字段名2）可以去重  
* where 字段名
  >（between _ and _    
  >in _  
  >is null  
  >not  
  >like % 或 _ ）  
* group by  （select后面只能跟参加分组的字段）
* order by 字段名1，字段名2 （desc：降序，asc：升序）
* 分组函数自动忽略了null数据（sum，count，min等）  
count（*）统计行数，count（具体字段）统计了该列不为空的数量  
* 分组函数不能用于where中，因为where在group by之前执行，没有组的概念，where只是从原始数据中取数。  
* having ：对分组之后的数据进行再次筛选（在计算后筛选出所需的数据进行显示，但where是先筛选后计算，where完成不了时才用having）

     

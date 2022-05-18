# C2 检索数据

~~~sql
# 单列查询
SELECT prod_name FROM Products;

# 多列查询
SELECT prod_id,prod_name,prod_price from Products;

# 检索所有
SELECT * FROM Products;

# 去重
SELECT DISTINCT vend_id from Products;
# 注：Distinct 作用于所有列，不能部分使用

# 限制行数
SELECT * from Products limit 5;
# 从第五行起返回5行数据 第一个检索的行是第0行
SELECT * FROM Products LIMIT 5 OFFSET 5;

~~~



## 挑战题

~~~sql
# 1
SELECT cust_id FROM Customers;

# 2
SELECT DISTINCT prod_id FROM OrderItems;

# 3
/* 注释
SELECT * FROM Customers;
*/
SELECT cust_id FROM Customers;
~~~


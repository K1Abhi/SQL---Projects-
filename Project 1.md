# 

## Solution

[View the complete code](https://github.com/YogeshOlla/8-Weeks-SQL-Challenge/blob/main/Case%20Study%201%20-%20Danny's%20Diner/SQL%20Code/Case%20Study%201%20-%20Danny's%20Diner.sql).

***

#### 1. In your company there hasn't been a database table with all the employee information yet.
####    You need to set up the table called employees in the following way:
![alt text](image.png)

#### There should be NOT NULL constraints for the following columns: first_name, last_name , job_position, start_date DATE,
#### birth_date DATE

````sql
Select S.customer_id, Sum(M.price) as Total_sales
From Menu m
Join Sales s
On m.product_id = s.product_id
Group by S.customer_id
````

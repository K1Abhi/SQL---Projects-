# 

## Solution

[View the complete code](https://github.com/YogeshOlla/8-Weeks-SQL-Challenge/blob/main/Case%20Study%201%20-%20Danny's%20Diner/SQL%20Code/Case%20Study%201%20-%20Danny's%20Diner.sql).

***

#### 1. In your company there hasn't been a database table with all the employee information yet. You need to set up the table called employees in the way shown bellow make sure there should be NOT NULL constraints for the following columns: first_name, last_name , job_position, start_date, birth_date:
![alt text](image.png)


````sql
CREATE TABLE employees
(
    emp_id INTEGER, 
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    job_position VARCHAR(50) NOT NULL,
    salary DECIMAL(8,2),
    start_date DATE NOT NULL,
    birth_date DATE NOT NULL,
    store_id INTEGER,
    department_id INTEGER, 
    manager_id INTEGER 
)
````

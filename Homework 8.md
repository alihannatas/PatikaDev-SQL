# SQL Course Homework 8



## Question 1



```sql
CREATE TABLE employee(

		id   INTEGER PRIMARY KEY,
		name VARCHAR(50),
		birthday DATE ,
		email VARCHAR(100)
);
```



## Question  2



```sql
---
```



##  Question  3



```sql
UPDATE employee 
SET  name = 'xxx',
	 email = 'yyy@yyy.y'
WHERE id > 39 AND id < 46  -- idisi 40, 41, 42, 43, 44, 45 olanlarin adi ve emaili guncellendi
RETURNING *;
```



##  Question  4



```sql
DELETE FROM employee 
WHERE id <6     -- idisi 6 dan kucuk olanlar silindi
RETURNING *;
```

### 																																							Alihan Atas
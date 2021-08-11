# SQL Course Homework 6



## Question 1



```sql
SELECT ROUND(AVG(rental_rate),4) FROM film;
```



## Question  2



```sql
SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';	
```



##  Question  3



```sql
SELECT MAX(length) FROM film 
WHERE rental_rate = 0.99;
```



##  Question  4



```sql
SELECT COUNT(DISTINCT replacement_cost)  
FROM film
WHERE length > 150;
```

### 																																							Alihan Atas


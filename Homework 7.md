# SQL Course Homework 7



## Question 1



```sql
SELECT rating, COUNT(title) 
FROM film
GROUP BY rating 
ORDER BY rating
```



## Question  2



```sql
SELECT replacement_cost, COUNT(title) 
FROM film
GROUP BY replacement_cost 
HAVING COUNT(title)>50
ORDER BY replacement_cost
```



##  Question  3



```sql
SELECT store_id, COUNT(customer) 
FROM customer
GROUP BY store_id
```



## Question 4



```sql
SELECT country_id, COUNT(*)
FROM city
GROUP BY country_id 
ORDER BY COUNT(*) DESC
LIMIT 1 
```



### 																																							Alihan Atas
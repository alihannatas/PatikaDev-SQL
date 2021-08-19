# SQL Course Homework 12



## Question 1



```sql
SELECT COUNT(*) FROM film 
WHERE length >
(SELECT AVG(length)  FROM film);
```



## Question  2



```sql
SELECT COUNT(*) FROM film 
WHERE  rental_rate = 
(SELECT MAX(rental_rate) FROM film);
```



##  Question  3



```sql
SELECT * FROM film 
WHERE  rental_rate = (SELECT MIN(rental_rate) FROM film) 
AND    
replacement_cost =  (SELECT MIN(replacement_cost) FROM film);
```



##  Question  4



```sql
SELECT first_name, last_name, SUM(amount) AS Toplam
FROM customer INNER JOIN payment 
ON customer.customer_id = payment.customer_id 
GROUP BY customer.customer_id 
ORDER BY Toplam DESC LIMIT 1;
```

### 																																							Alihan Atas
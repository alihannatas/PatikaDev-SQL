# SQL Course Homework 9



## Question 1



```sql
SELECT country.country,city.city  
FROM city 
INNER JOIN country 
ON city.country_id = country.country_id 
ORDER BY country.country
```



## Question  2



```sql
SELECT payment.payment_id, customer.first_name, customer.last_name 
FROM payment 
INNER JOIN customer 
ON payment.customer_id=customer.customer_id
```



##  Question  3



```sql
SELECT rental.rental_id, customer.first_name, customer.last_name 
FROM rental 
INNER JOIN customer 
ON rental.customer_id=customer.customer_id
```

### 																																							Alihan Atas
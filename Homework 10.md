# SQL Course Homework 10

## Question 1

```sql
SELECT city.city, country.country 
FROM city 
LEFT JOIN country 
ON city.country_id=country.country_id
ORDER BY country;
```

## Question 2

```sql
SELECT  payment.payment_id, customer.first_name, customer.last_name
FROM customer 
RIGHT JOIN payment 
ON customer.customer_id=payment.customer_id;
```

## Question 3

```sql
SELECT  rental.rental_id, customer.first_name, customer.last_name
FROM rental 
FULL JOIN customer 
ON customer.customer_id=rental.customer_id;
```

### Alihan Atas


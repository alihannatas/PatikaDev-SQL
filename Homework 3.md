# SQL Course Homework 3

## Question 1

```sql
SELECT * FROM country 
WHERE country LIKE 'A%a';
```

## Question 2

```sql
SELECT * FROM country
WHERE country LIKE '_____%n'
```

## Question 3

```sql
SELECT title FROM film  
WHERE title 
ILIKE '%t%t%t%t%'
```

## Question 4

```sql
SELECT * FROM film  
WHERE (title like 'C%')
AND   (length > 90)
AND   (rental_rate IN(2.99));
```



### Alihan Atas


# SQL Course Homework 11

## Question 1

```sql
(SELECT first_name FROM actor)
UNION 
(SELECT first_name FROM customer 
ORDER BY first_name)
```

## Question 2

```sql
(SELECT first_name FROM actor
INTERSECT
(SELECT first_name FROM customer
ORDER BY first_name)
```

## Question 3

```sql
(SELECT first_name FROM actor)
EXCEPT 
(SELECT first_name FROM customer ORDER BY first_name)
```

## Question 4

```sql
(SELECT first_name FROM actor)
UNION ALL
(SELECT first_name FROM customer 
ORDER BY first_name)

--Bu sorgu kesisim kumesindeki verileri aldigi icin ALL yazmanin hicbir anlami yok.
(SELECT first_name FROM actor
INTERSECT ALL
(SELECT first_name FROM customer
ORDER BY first_name)

--Bu sorgu ayrik  kumelerdeki verileri aldigi icin ALL yazmanin hicbir anlami yok. 
(SELECT first_name FROM actor)
EXCEPT ALL
(SELECT first_name FROM customer ORDER BY first_name) 
```



### Alihan Atas
# SQL KURSU ODEV 1



## Soru 1



```sql
SELECT title, description
FROM film;


```

## Soru 2



```sql
SELECT * FROM film
WHERE length> 60 AND length < 75;
```



##  Soru 3



```sql
SELECT * FROM film
WHERE rental_rate = 0.99 
AND replacement_cost = 12.99
OR replacement_cost = 28.99;
```



## Soru 4



```sql
sorgu = SELECT * FROM customer 
WHERE first_name = 'Mary';

Cevap =last_name = 'Smith'
```



## Soru 5



```sql
SELECT * FROM film 
WHERE length <= 50 
AND  rental_rate != 2.99 
OR  rental_rate != 4.99;

```



### 																																							Alihan Atas
## PATIKA.DEV-SQL-HW-1

<br>

## [Patka.dev](https://www.patika.dev/tr)

<br>

---

<br>

> Data-1 Commands

 ```sql

Select title, description 
From film

 ```
 
 <br>

 > Data-2 Commands

 ```sql

Select *
From film
Where length_film > 60 AND length_film < 75

 ```

<br>

> Data-3 Commands

```sql

Select *
From film
Where rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99)

```

<br>

> Data-4 Commands

```sql

Select first_name, last_name
From customer
Where first_name = 'Mary'

```

<br>

> Data-5 Commands

```sql

Select *
From film
Where length_film < 50 AND (rental_rate <> 2.99 OR rental_rate <> 4.99)

```

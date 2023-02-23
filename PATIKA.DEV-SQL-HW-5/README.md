## PATIKA.DEV-SQL-HW-5

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT *
FROM film
WHERE title LIKE '%n'
ORDER BY length_film DESC
LIMIT 5

```

<br>

> Data-2 Commands

```sql

SELECT *
FROM film
WHERE title LIKE '%n'
ORDER BY length_film ASC
OFFSET 5
LIMIT 5

```

<br>

> Data-3 Commands

```sql

SELECT *
FROM customer
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4

```

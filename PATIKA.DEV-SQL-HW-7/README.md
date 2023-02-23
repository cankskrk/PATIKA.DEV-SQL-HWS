## PATIKA.DEV-SQL-HW-7

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT rating, COUNT(*)
FROM film
GROUP BY rating

```

<br>

> Data-2 Commands

```sql

SELECT replacement_cost, COUNT(*)
FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50

```

<br>

> Data-3 Commands

```sql

SELECT store_id, COUNT(*)
FROM customer
GROUP BY store_id

```

<br>

> Data-4 Commands

```sql

SELECT country_id, COUNT(city_id)
FROM city
GROUP BY country_id
ORDER BY COUNT(*) DESC
LIMIT 1

```

<br>
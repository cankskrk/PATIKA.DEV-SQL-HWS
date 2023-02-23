## PATIKA.DEV-SQL-HW-6

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT AVG(rental_rate)
FROM film

```

<br>

> Data-2 Commands

```sql

SELECT COUNT(title)
FROM film
WHERE title LIKE 'C%'

```

<br>

> Data-3 Commands

```sql

SELECT MAX(length_film)
FROM film
WHERE rental_rate = 0.99

```

<br>

> Data-4 Commands

```sql

SELECT COUNT(DISTINCT replacement_cost)
FROM film
WHERE length_film > 150

```
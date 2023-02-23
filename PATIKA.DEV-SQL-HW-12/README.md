## PATIKA.DEV-SQL-HW-12

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT COUNT(title) FROM film
WHERE length_film > (SELECT AVG(length_film) FROM film)

```

<br>

> Data-2 Commands

```sql

SELECT COUNT(*) FROM film
WHERE rental_rate = (SELECT MAX(rental_rate) FROM film)

```

<br>

> Data-3 Commands

```sql

SELECT title FROM film
WHERE rental_rate = (SELECT MIN(rental_rate) FROM film) AND replacement_cost = (SELECT MIN(replacement_cost) FROM film)

```

<br>

> Data-4 Commands

```sql

SELECT customer_id, COUNT(payment_id) FROM payment
GROUP BY customer_id
ORDER BY COUNT(payment_id) desc

```

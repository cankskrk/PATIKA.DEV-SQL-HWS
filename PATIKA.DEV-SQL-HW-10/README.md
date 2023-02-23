## PATIKA.DEV-SQL-HW-10

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT city, country
FROM city
LEFT JOIN country
ON city.country_id = country.country_id

```

<br>

> Data-2 Commands

```sql

SELECT first_name, last_name, payment_id
FROM customer
RIGHT JOIN payment
ON customer.customer_id = payment.customer_id

```

<br>

> Data-3 Commands

```sql

SELECT first_name, last_name, rental_id
FROM customer
FULL JOIN rental
ON customer.customer_id = rental.customer_id

```

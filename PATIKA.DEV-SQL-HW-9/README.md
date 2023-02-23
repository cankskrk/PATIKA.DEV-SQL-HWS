## PATIKA.DEV-SQL-HW-9

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT city.city, country.country
FROM city
INNER JOIN country
ON city.city_id = country.country_id

```

<br>

> Data-2 Commands

```sql

SELECT payment_id, first_name, last_name
FROM customer
INNER JOIN payment
ON customer.customer_id = payment.customer_id

```

<br>

> Data-3 Commands

```sql

SELECT first_name, last_name, rental_id
FROM customer
INNER JOIN rental
ON customer.customer_id = rental.customer_id

```

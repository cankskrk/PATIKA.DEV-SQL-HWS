## PATIKA.DEV-SQL-HW-4

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Data-1 Commands

```sql

SELECT DISTINCT replacement_cost
FROM film

```

<br>

> Data-2 Commands

```sql

SELECT COUNT( DISTINCT replacement_cost )
FROM film

```

<br>

> Data-3 Commands

```sql

SELECT COUNT( title )
FROM film
WHERE title LIKE 'T%' AND rating = 'G'

```

<br>

> Data-4 Commands

```sql

SELECT COUNT( country )
FROM country
WHERE country ILIKE '_____'

```

<br>

> Data-5 Commands

```sql

SELECT COUNT( * )
FROM city
WHERE city ILIKE '%r'

```
```SQL
SELECT city.city, country.country FROM city LEFT JOIN country ON city.country_id = country.country_id;
SELECT payment.payment_id, customer.first_name, customer.last_name FROM customer RIGHT JOIN payment ON payment.customer_id = customer.customer_id;
SELECT rental.rental_id, customer.first_name, customer.last_name From customer FULL JOIN rental On rental.customer_id = customer.customer_id;
```

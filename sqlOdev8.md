```SQL
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
-- Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
UPDATE employee
SET 
	name = 'Guncellenen isim',
	email = 'Guncellenen email'
WHERE id BETWEEN 6 AND 12;
DELETE FROM employee WHERE id > 7;
```

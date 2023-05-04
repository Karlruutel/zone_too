# zone_too
SELECT * FROM books;
select * from books WHERE release_date >= 2010 AND type = "new" ORDER BY title ASC;
select title, release_date, price, type from books where release_date <= 1970 and type = "used" and price <= 20;
select year(order_date) as "aasta", count(*) "tellimuste arv" from orders group by year(order_date);

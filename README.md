yl21
1) SELECT * FROM d119358_tak22book.books;
2) select * from d119358_tak22book.books WHERE release_date >= 2010 AND type = "new" ORDER BY title ASC;
3) select title, release_date, price, type from d119358_tak22book.books where release_date <= 1970 and type = "used" and price <= 20; select year(order_date) as "aasta", count(*) "tellimuste arv" from orders group by year(order_date);
4) SELECT count(*) AS Tellimuste_arv, YEAR(order_date) AS Aasta  FROM d119358_tak22book.orders GROUP BY YEAR(order_date);

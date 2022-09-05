#### 1.test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```
`SELECT * FROM employee;`
#### 2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, email, birthday) values (1, 'Danella', 'dsegeswoeth0@github.io', null);
insert into employee (id, name, email, birthday) values (2, 'Doralyn', 'dbundey1@e-recht24.de', null);
insert into employee (id, name, email, birthday) values (3, 'Yul', 'yramsier2@ezinearticles.com', '1972-09-19');
insert into employee (id, name, email, birthday) values (4, 'Sherry', 'sgarret3@aol.com', null);
insert into employee (id, name, email, birthday) values (5, 'Ines', 'icredland4@nbcnews.com', '1946-05-31');
insert into employee (id, name, email, birthday) values (6, 'Haily', 'hgoffe5@bravesites.com', '1986-08-26');
insert into employee (id, name, email, birthday) values (7, 'Junette', null, '1943-02-28');
insert into employee (id, name, email, birthday) values (8, 'Grete', 'gpautot7@tiny.cc', '1963-11-12');
insert into employee (id, name, email, birthday) values (9, 'Fanechka', 'fottawell8@washingtonpost.com', '1985-01-09');
insert into employee (id, name, email, birthday) values (10, 'Virgilio', 'veuesden9@opera.com', '1941-08-04');
insert into employee (id, name, email, birthday) values (11, 'Lesli', 'lcurtissa@list-manage.com', '1978-06-21');
insert into employee (id, name, email, birthday) values (12, 'Brunhilda', 'bboliverb@ft.com', '1952-05-14');
insert into employee (id, name, email, birthday) values (13, 'Gratia', null, '1906-11-16');
insert into employee (id, name, email, birthday) values (14, 'Mickey', 'mclawsleyd@behance.net', '1916-06-16');
insert into employee (id, name, email, birthday) values (15, 'Codie', null, '1974-04-20');
insert into employee (id, name, email, birthday) values (16, 'Selene', 'scoatsf@hao123.com', null);
insert into employee (id, name, email, birthday) values (17, 'Alida', 'astanneyg@zdnet.com', '1982-04-02');
insert into employee (id, name, email, birthday) values (18, 'Auberon', 'adolligonh@webnode.com', '1960-03-12');
insert into employee (id, name, email, birthday) values (19, 'Esteban', 'ebecerrai@unblog.fr', null);
insert into employee (id, name, email, birthday) values (20, 'Monty', 'mprykej@newyorker.com', '1903-12-23');
insert into employee (id, name, email, birthday) values (21, 'Prentiss', 'pstoadk@rakuten.co.jp', '1954-07-20');
insert into employee (id, name, email, birthday) values (22, 'Elbertina', 'eskechleyl@disqus.com', null);
insert into employee (id, name, email, birthday) values (23, 'Janet', 'jfarnorthm@addthis.com', '1900-11-30');
insert into employee (id, name, email, birthday) values (24, 'Ashia', 'adartn@oracle.com', '1929-11-15');
insert into employee (id, name, email, birthday) values (25, 'Nissy', null, '1961-02-10');
insert into employee (id, name, email, birthday) values (26, 'Patrizia', 'pwoodstockp@wikispaces.com', null);
insert into employee (id, name, email, birthday) values (27, 'Rozele', 'rbandeyq@t.co', '1912-01-09');
insert into employee (id, name, email, birthday) values (28, 'Quintin', 'qmallindiner@weebly.com', null);
insert into employee (id, name, email, birthday) values (29, 'Ginger', 'ggreensets@unblog.fr', '1983-11-26');
insert into employee (id, name, email, birthday) values (30, 'Hercules', 'hdomanekt@opera.com', '1981-07-05');
insert into employee (id, name, email, birthday) values (31, 'Doretta', 'drennu@live.com', '1915-02-26');
insert into employee (id, name, email, birthday) values (32, 'Margot', 'mnuttyv@tmall.com', '1931-04-02');
insert into employee (id, name, email, birthday) values (33, 'Tybalt', 'tcoverdillw@networksolutions.com', null);
insert into employee (id, name, email, birthday) values (34, 'Willyt', 'wgrentx@123-reg.co.uk', null);
insert into employee (id, name, email, birthday) values (35, 'Cyndy', null, '1986-05-06');
insert into employee (id, name, email, birthday) values (36, 'Conn', 'cgoldenofirelandz@flavors.me', '1932-10-24');
insert into employee (id, name, email, birthday) values (37, 'Brandon', 'bbatram10@barnesandnoble.com', null);
insert into employee (id, name, email, birthday) values (38, 'Marcello', 'mdiboll11@weather.com', '1994-08-26');
insert into employee (id, name, email, birthday) values (39, 'Urbain', 'uenefer12@wikia.com', '1935-02-26');
insert into employee (id, name, email, birthday) values (40, 'Claudianus', 'csmythin13@senate.gov', '1903-05-17');
insert into employee (id, name, email, birthday) values (41, 'Kaitlynn', 'khales14@statcounter.com', null);
insert into employee (id, name, email, birthday) values (42, 'De', 'dtyers15@is.gd', '1957-06-26');
insert into employee (id, name, email, birthday) values (43, 'Alyce', 'acarvilla16@blogtalkradio.com', null);
insert into employee (id, name, email, birthday) values (44, 'Alex', 'amccuffie17@mysql.com', '1985-09-26');
insert into employee (id, name, email, birthday) values (45, 'Jarrid', null, null);
insert into employee (id, name, email, birthday) values (46, 'Wernher', 'wthyng19@smugmug.com', '1964-01-31');
insert into employee (id, name, email, birthday) values (47, 'Traci', 'tfolcarelli1a@usatoday.com', null);
insert into employee (id, name, email, birthday) values (48, 'Constanta', 'cgraysmark1b@slideshare.net', '1916-01-16');
insert into employee (id, name, email, birthday) values (49, 'Penni', 'pbellison1c@parallels.com', '1907-05-27');
insert into employee (id, name, email, birthday) values (50, 'Rawley', null, null);
```
`SELECT * FROM employee;`
#### 3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET name = 'AAAA',
	birthday = '1910-08-30',
	email = 'aaa@gmail.com'
WHERE id = 1;
UPDATE employee
SET name = 'BBBB',
	birthday = '1963-07-28',
	email = 'bbb@gmail.com'
WHERE id = 2;
UPDATE employee
SET name = 'CCCC',
	birthday = '1973-07-28',
	email = 'ccc@gmail.com'
WHERE id = 3;
UPDATE employee
SET name = 'DDD',
	birthday = '1963-07-28',
	email = 'ddd@gmail.com'
WHERE id = 4;
```
`SELECT * FROM employee;`
#### 4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE id IN(23, 24, 25, 26, 27);
```
`SELECT * FROM employee;`

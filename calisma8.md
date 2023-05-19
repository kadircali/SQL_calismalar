# test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);

```

# Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (name, birthday, email) values ('Rickard', '1980-12-05', 'rrogeron0@godaddy.com');
insert into employee (name, birthday, email) values ('Fairfax', '2015-09-10', 'ftrattles1@japanpost.jp');
insert into employee (name, birthday, email) values ('Anthiathia', '2000-01-05', 'acolthard2@techcrunch.com');
insert into employee (name, birthday, email) values ('Christiane', '1958-05-18', 'cdallinder3@lycos.com');
insert into employee (name, birthday, email) values ('Rene', '1991-03-01', 'rdeetlof4@tinypic.com');
insert into employee (name, birthday, email) values ('Farleigh', '1979-11-05', 'fmosdall5@admin.ch');
insert into employee (name, birthday, email) values ('Clemmy', '1921-08-05', 'cyewdall6@ihg.com');
insert into employee (name, birthday, email) values ('Celka', '1940-07-21', 'cbrumen7@google.cn');
insert into employee (name, birthday, email) values ('Dunn', '1972-02-21', 'dtukesby8@java.com');
insert into employee (name, birthday, email) values ('Hogan', '1989-09-03', 'hlytell9@weebly.com');
insert into employee (name, birthday, email) values ('Hadley', '2004-05-19', 'hstorkesa@nymag.com');
insert into employee (name, birthday, email) values ('Gerardo', '1915-06-20', 'gfearyb@dyndns.org');
insert into employee (name, birthday, email) values ('Rand', '1961-01-21', 'rygouc@shutterfly.com');
insert into employee (name, birthday, email) values ('Levi', '1999-05-09', 'lvalerod@netlog.com');
insert into employee (name, birthday, email) values ('Kerk', '1935-01-21', 'kaskhame@blogtalkradio.com');
insert into employee (name, birthday, email) values ('Yolande', '1945-01-23', 'ypolakf@icio.us');
insert into employee (name, birthday, email) values ('Babette', '1977-02-25', 'bluxtong@wix.com');
insert into employee (name, birthday, email) values ('Florence', '1931-04-22', 'fbathoh@google.it');
insert into employee (name, birthday, email) values ('Traver', '2019-11-17', 'tserotskyi@vimeo.com');
insert into employee (name, birthday, email) values ('Halimeda', '1933-05-10', 'hghelerdinij@un.org');
insert into employee (name, birthday, email) values ('Deanna', '1965-01-28', 'dquilkink@4shared.com');
insert into employee (name, birthday, email) values ('Mellicent', '1993-10-17', 'mkingzettl@businessweek.com');
insert into employee (name, birthday, email) values ('Sansone', '1944-04-23', 'sjoynesm@wordpress.org');
insert into employee (name, birthday, email) values ('Lionel', '2012-09-19', 'lcaviln@nbcnews.com');
insert into employee (name, birthday, email) values ('Frederick', '1911-07-30', 'fcrowesto@exblog.jp');
insert into employee (name, birthday, email) values ('Rozele', '1940-04-13', 'rrhysp@so-net.ne.jp');
insert into employee (name, birthday, email) values ('Marquita', '1946-08-25', 'mbalducciq@twitter.com');
insert into employee (name, birthday, email) values ('Ariel', '1947-03-17', 'acozensr@barnesandnoble.com');
insert into employee (name, birthday, email) values ('Kurt', '1983-12-31', 'kcaskies@ovh.net');
insert into employee (name, birthday, email) values ('Pail', '1970-11-12', 'pgarmentt@blogger.com');
insert into employee (name, birthday, email) values ('Marjy', '1993-06-21', 'mcaldesu@narod.ru');
insert into employee (name, birthday, email) values ('Aleen', '1911-10-25', 'apfifferv@bandcamp.com');
insert into employee (name, birthday, email) values ('Estrella', '1930-11-21', 'eludlamw@xing.com');
insert into employee (name, birthday, email) values ('Andreas', '1923-11-13', 'agatlandx@yandex.ru');
insert into employee (name, birthday, email) values ('Loralyn', '2021-10-03', 'lyoudelly@surveymonkey.com');
insert into employee (name, birthday, email) values ('Jehanna', '1945-09-11', 'jkettleyz@whitehouse.gov');
insert into employee (name, birthday, email) values ('Olivero', '1969-09-25', 'otebbutt10@deliciousdays.com');
insert into employee (name, birthday, email) values ('Malena', '1967-10-23', 'mreeks11@delicious.com');
insert into employee (name, birthday, email) values ('Katalin', '1932-06-18', 'kblatchford12@webeden.co.uk');
insert into employee (name, birthday, email) values ('Minny', '1907-03-05', 'mmartinon13@bizjournals.com');
insert into employee (name, birthday, email) values ('El', '1980-06-12', 'ecurrier14@biglobe.ne.jp');
insert into employee (name, birthday, email) values ('Waldemar', '1939-09-30', 'wlohoar15@flavors.me');
insert into employee (name, birthday, email) values ('Maddie', '1939-01-12', 'mmckeand16@sohu.com');
insert into employee (name, birthday, email) values ('Elfrida', '1967-01-15', 'ecullivan17@furl.net');
insert into employee (name, birthday, email) values ('Callie', '1941-01-23', 'cmuzzillo18@t-online.de');
insert into employee (name, birthday, email) values ('Brandie', '1981-04-12', 'brobertsson19@sohu.com');
insert into employee (name, birthday, email) values ('Laurie', '2013-07-21', 'lhatcliffe1a@1und1.de');
insert into employee (name, birthday, email) values ('Sergei', '2011-08-29', 'sfawdrie1b@salon.com');
insert into employee (name, birthday, email) values ('Ulrick', '2010-11-09', 'ufeatherstone1c@themeforest.net');
insert into employee (name, birthday, email) values ('Genevieve', '1908-04-14', 'glynd1d@ebay.com');

```

# Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee
SET
	name='Brandon'
WHERE name='Rand'
RETURNING *;
--------------
UPDATE employee
SET
	name ='Halsey'
WHERE  id=10;
--------------
UPDATE employee
SET
	birthday='1995-04-05'
WHERE email='ecurrier14@biglobe.ne.jp';
----------------------
UPDATE employee
SET
	email='postgre@sql.com'
WHERE id=1;
-----------------------------
UPDATE employee
SET
	name = 'Patika'
WHERE name LIKE 'L%'
RETURNING *;
```

# Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE FROM employee
WHERE name = 'Rickard';
----------------------
DELETE FROM employee
WHERE id = 9;
-----------------
DELETE FROM employee
WHERE birthday = '1999-05-09';
-----------------------------------
DELETE FROM employee
WHERE email= 'kblatchford12@webeden.co.uk';
---------------------------------------
DELETE FROM employee
WHERE name LIKE 'S%';

```




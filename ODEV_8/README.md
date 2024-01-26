# Ödev-8 Soru Çözümleri

1. **test** veritabanınızda **employee** isimli sütun bilgileri **id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100)** olan bir tablo oluşturalım.

```
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

2. Oluşturduğumuz employee tablosuna '**Mockaroo**' servisini kullanarak **50 adet** veri ekleyelim.

```
insert into employee (id, name, email, birthday) values (1, 'Benito', null, '1944-09-28');
insert into employee (id, name, email, birthday) values (2, 'Priscilla', 'pbohlens1@loc.gov', '2001-06-07');
insert into employee (id, name, email, birthday) values (3, null, 'fkalberer2@plala.or.jp', '2017-05-21');
insert into employee (id, name, email, birthday) values (4, 'Marleen', null, '2012-09-25');
insert into employee (id, name, email, birthday) values (5, 'Bronnie', 'bdelaharpe4@omniture.com', '2016-04-16');
insert into employee (id, name, email, birthday) values (6, 'Alina', 'asaxton5@miitbeian.gov.cn', '1999-05-31');
insert into employee (id, name, email, birthday) values (7, 'Meridel', 'mstraine6@wisc.edu', '1960-08-16');
insert into employee (id, name, email, birthday) values (8, 'Dave', 'dmassimi7@amazon.com', '2004-06-07');
insert into employee (id, name, email, birthday) values (9, 'Meryl', null, '1950-03-16');
insert into employee (id, name, email, birthday) values (10, 'Kass', 'kbraune9@chronoengine.com', null);
insert into employee (id, name, email, birthday) values (11, 'Saunder', 'sseneschala@dell.com', '2020-01-29');
insert into employee (id, name, email, birthday) values (12, 'Rubetta', 'rbramhillb@wikispaces.com', '1951-04-16');
insert into employee (id, name, email, birthday) values (13, 'Vincenty', 'vgartlandc@redcross.org', '1997-03-11');
insert into employee (id, name, email, birthday) values (14, 'Teresina', 'tlined@sakura.ne.jp', null);
insert into employee (id, name, email, birthday) values (15, 'Jilleen', 'joriele@constantcontact.com', '2005-08-13');
insert into employee (id, name, email, birthday) values (16, 'Christine', 'chelliwellf@4shared.com', '2005-02-15');
insert into employee (id, name, email, birthday) values (17, 'Shane', 'soffag@squidoo.com', '2007-02-16');
insert into employee (id, name, email, birthday) values (18, 'Farly', null, '1997-02-09');
insert into employee (id, name, email, birthday) values (19, 'Owen', 'opocockei@reuters.com', null);
insert into employee (id, name, email, birthday) values (20, 'Bell', 'bmarvenj@zimbio.com', '1951-01-12');
insert into employee (id, name, email, birthday) values (21, 'Borden', 'bferonk@go.com', '1999-11-08');
insert into employee (id, name, email, birthday) values (22, null, 'rgerauldl@godaddy.com', null);
insert into employee (id, name, email, birthday) values (23, 'Hildagard', 'hgerholzm@cnn.com', null);
insert into employee (id, name, email, birthday) values (24, 'Leigh', 'lhudlessn@tumblr.com', '1955-04-24');
insert into employee (id, name, email, birthday) values (25, 'Thatch', 'tcuthbertsono@istockphoto.com', '1992-12-17');
insert into employee (id, name, email, birthday) values (26, 'Erich', null, null);
insert into employee (id, name, email, birthday) values (27, 'Gnni', 'gwhyattq@ebay.co.uk', '1996-05-08');
insert into employee (id, name, email, birthday) values (28, 'Maighdiln', 'mruslinr@booking.com', '1989-10-22');
insert into employee (id, name, email, birthday) values (29, 'Misty', null, null);
insert into employee (id, name, email, birthday) values (30, 'Shel', 'skellet@hexun.com', null);
insert into employee (id, name, email, birthday) values (31, 'Barnard', 'bwilkissonu@hubpages.com', null);
insert into employee (id, name, email, birthday) values (32, 'Fredelia', 'fweddeburnscrimgeourv@vkontakte.ru', null);
insert into employee (id, name, email, birthday) values (33, 'Pauletta', 'pbroadwellw@skyrock.com', null);
insert into employee (id, name, email, birthday) values (34, 'Kristoffer', 'kschneiderx@blogger.com', '1957-10-11');
insert into employee (id, name, email, birthday) values (35, 'Florenza', 'fsymingtony@unicef.org', '1959-01-16');
insert into employee (id, name, email, birthday) values (36, 'Ogden', 'ofiridolfiz@stumbleupon.com', null);
insert into employee (id, name, email, birthday) values (37, 'Klaus', 'ktrowill10@fastcompany.com', '2002-12-20');
insert into employee (id, name, email, birthday) values (38, 'Tatiania', 'tokie11@intel.com', null);
insert into employee (id, name, email, birthday) values (39, 'Clerc', 'cpassey12@go.com', '1983-04-05');
insert into employee (id, name, email, birthday) values (40, 'Tobie', 'tmushawe13@thetimes.co.uk', '1942-02-14');
insert into employee (id, name, email, birthday) values (41, 'Aurea', 'aprosh14@qq.com', '2007-08-14');
insert into employee (id, name, email, birthday) values (42, 'Jemimah', 'jmussalli15@indiegogo.com', '1960-02-08');
insert into employee (id, name, email, birthday) values (43, 'Cherice', 'cillesley16@intel.com', '1988-08-25');
insert into employee (id, name, email, birthday) values (44, null, 'rfabri17@google.pl', '1966-12-21');
insert into employee (id, name, email, birthday) values (45, 'Merell', 'mcrowden18@usgs.gov', '1953-02-15');
insert into employee (id, name, email, birthday) values (46, 'Sidonia', 'swinsor19@sfgate.com', '1999-05-18');
insert into employee (id, name, email, birthday) values (47, 'Eduardo', 'eprofit1a@si.edu', '1989-03-04');
insert into employee (id, name, email, birthday) values (48, 'Lukas', 'lveel1b@slashdot.org', '1965-05-10');
insert into employee (id, name, email, birthday) values (49, 'Abbey', 'amila1c@ebay.com', '2003-05-20');
insert into employee (id, name, email, birthday) values (50, 'Kamillah', 'kgalvin1d@jiathis.com', '1952-02-26');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek **5 adet UPDATE** işlemi yapalım.

```
UPDATE employee
SET name = 'John'
WHERE id = 3;

UPDATE employee
SET name = 'Adam'
WHERE id = 6;

UPDATE employee
SET birthday = '1944-09-29'
WHERE id = 1;

UPDATE employee
SET birthday = '1900-01-01'
WHERE name LIKE 'V%';

UPDATE employee
SET email = 'sasasass@asfasf.com'
WHERE name = 'Benito';
```

4. Sütunların her birine göre ilgili satırı silecek **5 adet DELETE** işlemi yapalım.

```
DELETE FROM employee
WHERE id IN (3,6,9)
RETURNING *;

DELETE FROM employee
WHERE CHAR_LENGTH(email)> 25
RETURNING *;

DELETE FROM employee
WHERE name LIKE 'V%'
RETURNING *;

DELETE FROM employee
WHERE birthday = '1900-01-01'
RETURNING *;

DELETE FROM employee
WHERE name IS NULL
RETURNING *;
```

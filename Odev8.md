# Ödev 8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
```
insert into employee (id, name, birthday, email) values (1, 'Carmine', '2023-11-25', 'cbozworth0@dyndns.org');
insert into employee (id, name, birthday, email) values (2, 'Mirelle', '2023-10-29', 'mhasel1@nytimes.com');
insert into employee (id, name, birthday, email) values (3, 'Brion', '2023-11-11', 'bwestwood2@usnews.com');
insert into employee (id, name, birthday, email) values (4, 'Brocky', '2023-12-07', 'bfeore3@springer.com');
insert into employee (id, name, birthday, email) values (5, 'Bernadette', '2023-02-06', 'bcassell4@github.com');
insert into employee (id, name, birthday, email) values (6, 'Kitti', '2023-07-14', 'kdemageard5@blogspot.com');
insert into employee (id, name, birthday, email) values (7, 'Gwenora', '2023-06-21', 'gseedull6@elegantthemes.com');
insert into employee (id, name, birthday, email) values (8, 'Lucky', '2023-03-31', 'lloudian7@businessweek.com');
insert into employee (id, name, birthday, email) values (9, 'Fredric', '2023-09-08', 'fbusst8@nhs.uk');
insert into employee (id, name, birthday, email) values (10, 'Ward', '2023-03-18', 'wcullinan9@craigslist.org');
insert into employee (id, name, birthday, email) values (11, 'Keelia', '2023-07-22', 'kschulta@ed.gov');
insert into employee (id, name, birthday, email) values (12, 'Etti', '2023-08-12', 'ebehrensb@imgur.com');
insert into employee (id, name, birthday, email) values (13, 'Thekla', '2023-05-02', 'tissonc@t.co');
insert into employee (id, name, birthday, email) values (14, 'Jane', '2023-03-04', 'jdyed@princeton.edu');
insert into employee (id, name, birthday, email) values (15, 'Siobhan', '2023-04-12', 'streese@tamu.edu');
insert into employee (id, name, birthday, email) values (16, 'Jacquelyn', '2023-01-21', 'jsteetf@ifeng.com');
insert into employee (id, name, birthday, email) values (17, 'Tory', '2023-12-23', 'twhettletong@earthlink.net');
insert into employee (id, name, birthday, email) values (18, 'Rose', '2023-01-20', 'rlyptradeh@geocities.com');
insert into employee (id, name, birthday, email) values (19, 'Bekki', '2023-05-26', 'brivetti@sogou.com');
insert into employee (id, name, birthday, email) values (20, 'Rennie', '2023-04-12', 'rmattinglyj@marketwatch.com');
insert into employee (id, name, birthday, email) values (21, 'Courtnay', '2023-06-04', 'cgreenalfk@ted.com');
insert into employee (id, name, birthday, email) values (22, 'Roxanna', '2023-01-26', 'rcanapel@163.com');
insert into employee (id, name, birthday, email) values (23, 'Kayle', '2023-10-06', 'kfarfolomeevm@comcast.net');
insert into employee (id, name, birthday, email) values (24, 'Loreen', '2023-07-07', 'lbootn@google.ru');
insert into employee (id, name, birthday, email) values (25, 'Sheila-kathryn', '2023-10-30', 'slomasnao@rakuten.co.jp');
insert into employee (id, name, birthday, email) values (26, 'Marianna', '2023-11-18', 'mbrimblecombp@fastcompany.com');
insert into employee (id, name, birthday, email) values (27, 'Janette', '2023-03-15', 'jcunniffeq@livejournal.com');
insert into employee (id, name, birthday, email) values (28, 'Seana', '2023-06-05', 'scurlessr@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (29, 'Chrystel', '2023-11-26', 'cbrannans@dyndns.org');
insert into employee (id, name, birthday, email) values (30, 'Chevy', '2023-10-10', 'cfowellt@ebay.co.uk');
insert into employee (id, name, birthday, email) values (31, 'Rodolphe', '2022-12-31', 'rswannacku@uiuc.edu');
insert into employee (id, name, birthday, email) values (32, 'Timmy', '2023-03-29', 'tmorriesonv@china.com.cn');
insert into employee (id, name, birthday, email) values (33, 'Daryn', '2023-02-10', 'dsayrew@sakura.ne.jp');
insert into employee (id, name, birthday, email) values (34, 'Torry', '2023-12-05', 'ttumiltyx@hc360.com');
insert into employee (id, name, birthday, email) values (35, 'Ozzy', '2023-11-19', 'ogaily@fotki.com');
insert into employee (id, name, birthday, email) values (36, 'Burton', '2023-06-21', 'babelez@unblog.fr');
insert into employee (id, name, birthday, email) values (37, 'Kele', '2023-05-10', 'kbraiden10@chronoengine.com');
insert into employee (id, name, birthday, email) values (38, 'Alan', '2023-05-14', 'ahazlehurst11@gmpg.org');
insert into employee (id, name, birthday, email) values (39, 'Ingelbert', '2023-09-25', 'isnel12@surveymonkey.com');
insert into employee (id, name, birthday, email) values (40, 'Free', '2023-10-27', 'fclowser13@example.com');
insert into employee (id, name, birthday, email) values (41, 'Blinny', '2023-06-13', 'bsirette14@slate.com');
insert into employee (id, name, birthday, email) values (42, 'Ralph', '2023-02-18', 'rbowness15@earthlink.net');
insert into employee (id, name, birthday, email) values (43, 'Jackson', '2023-04-01', 'jcocozza16@cafepress.com');
insert into employee (id, name, birthday, email) values (44, 'Barris', '2023-05-14', 'bhutley17@samsung.com');
insert into employee (id, name, birthday, email) values (45, 'Reginald', '2023-12-22', 'rdelagua18@amazon.com');
insert into employee (id, name, birthday, email) values (46, 'Isadora', '2023-12-07', 'imorena19@ox.ac.uk');
insert into employee (id, name, birthday, email) values (47, 'Patrice', '2023-12-15', 'psanpere1a@dion.ne.jp');
insert into employee (id, name, birthday, email) values (48, 'Madelena', '2023-06-05', 'mcookman1b@disqus.com');
insert into employee (id, name, birthday, email) values (49, 'Gwenni', '2023-01-01', 'gkeerl1c@arstechnica.com');
insert into employee (id, name, birthday, email) values (50, 'Tonya', '2023-05-21', 'tclues1d@netvibes.com');
```
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
```
UPDATE employee SET name = 'Ege Batug Kocak' WHERE id=1;
UPDATE employee SET email = 'randommail@hotmail.com' WHERE name ='Reginald' RETURNING *;
UPDATE employee SET birthday = '2000-02-02' WHERE id=30;
UPDATE employee SET name = 'Mete Dundar', birthday = '2003-09-11', email = 'mete@dundar.com' WHERE id=2;
UPDATE employee SET name = 'UPDATE' WHERE birthday = '2023-02-18';
```
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```
DELETE employee WHERE id=6;
DELETE employee WHERE name='Patrice';
DELETE employee WHERE birthday='2023-01-01' RETURNING *;
DELETE employee WHERE name='Tonya';
DELETE employee WHERE name='Jackson' AND id=43;
```

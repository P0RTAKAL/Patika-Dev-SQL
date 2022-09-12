SQL Ödev 8
----------


1) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

CREATE TABLE employee (
  id SERIAL PRIMARY KEY,
  name VARCHAR(50),
  birthday DATE
  email VARCHAR(100)
);

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

2) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

insert into employee (id, name, birthday, email) values (1, 'Bernardo Hamelyn', '17/6/1973', 'bhamelyn0@seesaa.net');
insert into employee (id, name, birthday, email) values (2, 'Bernita Oakley', '7/1/1950', 'boakley1@hao123.com');
insert into employee (id, name, birthday, email) values (3, 'Iosep Buckeridge', '16/7/1950', 'ibuckeridge2@geocities.com');
insert into employee (id, name, birthday, email) values (4, 'Rafi Hoston', '1/5/1974', 'rhoston3@imdb.com');
insert into employee (id, name, birthday, email) values (5, 'Fred Shwalbe', '3/4/2002', 'fshwalbe4@umn.edu');
insert into employee (id, name, birthday, email) values (6, 'Tallulah Dionisii', '29/5/1984', 'tdionisii5@etsy.com');
insert into employee (id, name, birthday, email) values (7, 'Tessi Penson', '31/8/1978', 'tpenson6@paginegialle.it');
insert into employee (id, name, birthday, email) values (8, 'Hildegaard Fellos', '2/7/1986', 'hfellos7@craigslist.org');
insert into employee (id, name, birthday, email) values (9, 'Gianna Shadfourth', '4/3/1977', 'gshadfourth8@google.com.au');
insert into employee (id, name, birthday, email) values (10, 'Camille Brient', '6/7/1954', 'cbrient9@zimbio.com');
insert into employee (id, name, birthday, email) values (11, 'Gerrie Dyster', '28/9/1963', 'gdystera@businessweek.com');
insert into employee (id, name, birthday, email) values (12, 'Niel Jeffery', '30/8/1991', 'njefferyb@chron.com');
insert into employee (id, name, birthday, email) values (13, 'Timothea Teasdale', '16/8/2003', 'tteasdalec@example.com');
insert into employee (id, name, birthday, email) values (14, 'Ynez Rawsthorne', '6/7/1994', 'yrawsthorned@oakley.com');
insert into employee (id, name, birthday, email) values (15, 'Channa Loynton', '28/1/1985', 'cloyntone@shareasale.com');
insert into employee (id, name, birthday, email) values (16, 'Milka Armsby', '29/10/1951', 'marmsbyf@ow.ly');
insert into employee (id, name, birthday, email) values (17, 'Isadore Bilyard', '16/10/1988', 'ibilyardg@stanford.edu');
insert into employee (id, name, birthday, email) values (18, 'Ethelyn Grinvalds', '3/2/2000', 'egrinvaldsh@bigcartel.com');
insert into employee (id, name, birthday, email) values (19, 'Merci Snufflebottom', '1/5/1992', 'msnufflebottomi@dyndns.org');
insert into employee (id, name, birthday, email) values (20, 'Jillayne Lewsy', '20/11/1981', 'jlewsyj@utexas.edu');
insert into employee (id, name, birthday, email) values (21, 'Vanna Goolden', '20/4/1971', 'vgooldenk@arizona.edu');
insert into employee (id, name, birthday, email) values (22, 'Quinn Paulton', '17/4/1968', 'qpaultonl@youku.com');
insert into employee (id, name, birthday, email) values (23, 'Loleta Smoth', '31/3/1957', 'lsmothm@alibaba.com');
insert into employee (id, name, birthday, email) values (24, 'Aldo Filoniere', '7/7/1967', 'afilonieren@ifeng.com');
insert into employee (id, name, birthday, email) values (25, 'Vannie Impy', '17/3/1962', 'vimpyo@java.com');
insert into employee (id, name, birthday, email) values (26, 'Carolee Broady', '27/2/1995', 'cbroadyp@engadget.com');
insert into employee (id, name, birthday, email) values (27, 'Gabrila Yannoni', '6/1/2003', 'gyannoniq@ox.ac.uk');
insert into employee (id, name, birthday, email) values (28, 'Guendolen Jefferys', '22/7/1964', 'gjefferysr@qq.com');
insert into employee (id, name, birthday, email) values (29, 'Gizela Tresise', '24/6/1999', 'gtresises@twitpic.com');
insert into employee (id, name, birthday, email) values (30, 'Merla Guye', '3/12/1988', 'mguyet@amazon.co.uk');
insert into employee (id, name, birthday, email) values (31, 'Bendicty Pharrow', '30/4/1995', 'bpharrowu@japanpost.jp');
insert into employee (id, name, birthday, email) values (32, 'Emelda Matthai', '28/4/1954', 'ematthaiv@psu.edu');
insert into employee (id, name, birthday, email) values (33, 'Olive Zelner', '29/4/2003', 'ozelnerw@utexas.edu');
insert into employee (id, name, birthday, email) values (34, 'Tomlin Fouch', '13/9/1974', 'tfouchx@imdb.com');
insert into employee (id, name, birthday, email) values (35, 'Beilul Whacket', '28/2/1978', 'bwhackety@cyberchimps.com');
insert into employee (id, name, birthday, email) values (36, 'Gibbie Cadigan', '4/1/1969', 'gcadiganz@chicagotribune.com');
insert into employee (id, name, birthday, email) values (37, 'Cordy Jerosch', '27/7/1951', 'cjerosch10@abc.net.au');
insert into employee (id, name, birthday, email) values (38, 'Aldridge Stote', '10/10/1964', 'astote11@pbs.org');
insert into employee (id, name, birthday, email) values (39, 'Karoline Anfusso', '20/3/1996', 'kanfusso12@joomla.org');
insert into employee (id, name, birthday, email) values (40, 'Maggi Berth', '13/7/1973', 'mberth13@example.com');
insert into employee (id, name, birthday, email) values (41, 'Bartlett Aldersley', '15/2/1957', 'baldersley14@samsung.com');
insert into employee (id, name, birthday, email) values (42, 'Armstrong Redford', '12/3/1997', 'aredford15@weather.com');
insert into employee (id, name, birthday, email) values (43, 'Truman McConachie', '17/5/2001', 'tmcconachie16@prlog.org');
insert into employee (id, name, birthday, email) values (44, 'Deana Sempill', '16/3/1991', 'dsempill17@senate.gov');
insert into employee (id, name, birthday, email) values (45, 'Mala Meece', '23/12/1957', 'mmeece18@census.gov');
insert into employee (id, name, birthday, email) values (46, 'Kyle Nickols', '17/9/2001', 'knickols19@chicagotribune.com');
insert into employee (id, name, birthday, email) values (47, 'Nicky Mourant', '30/5/1993', 'nmourant1a@istockphoto.com');
insert into employee (id, name, birthday, email) values (48, 'Mirilla Farrans', '6/2/1972', 'mfarrans1b@statcounter.com');
insert into employee (id, name, birthday, email) values (49, 'Sax Hukin', '22/12/1963', 'shukin1c@uol.com.br');
insert into employee (id, name, birthday, email) values (50, 'Ardenia Geistmann', '23/11/1972', 'ageistmann1d@nsw.gov.au');



-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

UPDATE employee
SET name = 'A*** B*** ',
	birthday = '01/01/1950',
	email = 'abc@dfg.com',
WHERE id = 1;

UPDATE employee
SET name = 'C*** D*** ',
	birthday = '01/01/1960',
	email = 'dfg@dfg.com',
WHERE id = 2;

UPDATE employee
SET name = 'E*** F*** ',
	birthday = '01/01/1970',
	email = 'hij@dfg.com',
WHERE id = 3;

UPDATE employee
SET name = 'G*** H*** ',
	birthday = '01/01/1980',
	email = 'klm@dfg.com',
WHERE id = 4;

UPDATE employee
SET name = 'J*** K*** ',
	birthday = '01/01/1990',
	email = 'nop@dfg.com',
WHERE id = 5;

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

DELETE FROM employee WHERE id = 50;
DELETE FROM employee WHERE id = 49;
DELETE FROM employee WHERE id = 48;
DELETE FROM employee WHERE id = 47;
DELETE FROM employee WHERE id = 46;


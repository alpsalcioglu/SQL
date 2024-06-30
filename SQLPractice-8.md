# SQLPractice-8

1. test veritabanınızda employee isimli sütun bilgileri 
   id(INTEGER), name VARCHAR(50), birthday DATE, email 
   VARCHAR(100) olan bir tablo oluşturalım.

* CREATE TABLE employee(
* id INTEGER NOT NULL,
* name VARCHAR(50) NOT NULL,
* birthday DATE 
* email VARCHAR(100)
* );

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini 
   kullanarak 50 adet veri ekleyelim.
   
* insert into employee (id, name, birthday, email) values (1, 'Allene', '1997-07-01', 'aroyan0@phoca.cz');
* insert into employee (id, name, birthday, email) values (2, 'Raddie', '1996-07-03', 'rstoltz1@nbcnews.com');
* insert into employee (id, name, birthday, email) values (3, 'Jorry', '1991-07-05', 'jwickes2@hubpages.com');
* insert into employee (id, name, birthday, email) values (4, 'Ashlan', '1993-07-01', 'abonhan3@hao123.com');
* insert into employee (id, name, birthday, email) values (5, 'Marten', '1997-06-02', 'mgirardin4@chicagotribune.com');
* insert into employee (id, name, birthday, email) values (6, 'Sig', '1990-10-09', 'shawkey5@digg.com');
* insert into employee (id, name, birthday, email) values (7, 'Danella', '1995-12-07', 'dmccrisken6@house.gov');
* insert into employee (id, name, birthday, email) values (8, 'Ebenezer', '1994-08-25', 'ehanner7@chron.com');
* insert into employee (id, name, birthday, email) values (9, 'Valaria', '1991-03-30', 'vsweeny8@cpanel.net');
* insert into employee (id, name, birthday, email) values (10, 'Mair', null, 'mdobinson9@about.com');
* insert into employee (id, name, birthday, email) values (11, 'Reube', '2000-02-01', null);
* insert into employee (id, name, birthday, email) values (12, 'Minnnie', '1997-03-05', 'mbendittb@slideshare.net');
* insert into employee (id, name, birthday, email) values (13, 'Cullen', '1994-01-08', 'cfantonc@surveymonkey.com');
* insert into employee (id, name, birthday, email) values (14, 'Raffaello', '1991-04-15', 'rapplebyd@meetup.com');
* insert into employee (id, name, birthday, email) values (15, 'Lynn', '1992-09-12', 'lbrailsforde@tumblr.com');
* insert into employee (id, name, birthday, email) values (16, 'Valerie', null, null);
* insert into employee (id, name, birthday, email) values (17, 'Linda', '1997-07-19', 'lkristufekg@scientificamerican.com');
* insert into employee (id, name, birthday, email) values (18, 'Rebeka', '1992-09-14', null);
* insert into employee (id, name, birthday, email) values (19, 'Ealasaid', '1994-08-07', 'eplosei@tripadvisor.com');
* insert into employee (id, name, birthday, email) values (20, 'Rhodie', '1995-06-08', 'rlamacraftj@bloglovin.com');
* insert into employee (id, name, birthday, email) values (21, 'Ulrich', '1992-12-21', 'ucrosgrovek@4shared.com');
* insert into employee (id, name, birthday, email) values (22, 'Beniamino', '1991-08-22', 'bcasierl@miibeian.gov.cn');
* insert into employee (id, name, birthday, email) values (23, 'Vivienne', null, 'vdowtym@biglobe.ne.jp');
* insert into employee (id, name, birthday, email) values (24, 'Morey', '1995-02-06', 'mbumfreyn@desdev.cn');
* insert into employee (id, name, birthday, email) values (25, 'Donelle', '2000-04-07', 'dlaugherano@bloomberg.com');
* insert into employee (id, name, birthday, email) values (26, 'Ulberto', '2000-04-01', 'ubryantp@washington.edu');
* insert into employee (id, name, birthday, email) values (27, 'Malachi', '1999-07-26', 'mgrunsonq@thetimes.co.uk');
* insert into employee (id, name, birthday, email) values (28, 'Valentine', '1990-10-25', 'vphilpotr@parallels.com');
* insert into employee (id, name, birthday, email) values (29, 'Calla', '1994-03-06', 'clightowlers@ameblo.jp');
* insert into employee (id, name, birthday, email) values (30, 'Jerrome', '1996-08-07', 'jpallatinat@miibeian.gov.cn');
* insert into employee (id, name, birthday, email) values (31, 'Iosep', '1991-06-11', 'ipeattu@cornell.edu');
* insert into employee (id, name, birthday, email) values (32, 'Siana', '1993-11-18', 'scarayolv@over-blog.com');
* insert into employee (id, name, birthday, email) values (33, 'Otes', '1996-01-09', 'olanghornew@yale.edu');
* insert into employee (id, name, birthday, email) values (34, 'Douglass', '1995-01-02', 'dglenwrightx@narod.ru');
* insert into employee (id, name, birthday, email) values (35, 'Opalina', '1992-01-22', 'ooverally@senate.gov');
* insert into employee (id, name, birthday, email) values (36, 'Phineas', '1998-07-05', null);
* insert into employee (id, name, birthday, email) values (37, 'Marlyn', '1998-03-14', 'mjuett10@wikipedia.org');
* insert into employee (id, name, birthday, email) values (38, 'Caprice', '1996-05-29', 'choyland11@sogou.com');
* insert into employee (id, name, birthday, email) values (39, 'Mona', '1992-05-02', 'medmund12@vimeo.com');
* insert into employee (id, name, birthday, email) values (40, 'Ewan', '1990-07-18', 'ewinders13@mayoclinic.com');
* insert into employee (id, name, birthday, email) values (41, 'Kanya', '1997-12-23', 'kmeasham14@salon.com');
* insert into employee (id, name, birthday, email) values (42, 'Leland', '1991-02-26', 'lvigneron15@lulu.com');
* insert into employee (id, name, birthday, email) values (43, 'Ferguson', '1995-11-12', 'fgaisford16@facebook.com');
* insert into employee (id, name, birthday, email) values (44, 'Donna', '1990-10-21', 'dpotter17@bravesites.com');
* insert into employee (id, name, birthday, email) values (45, 'Rhodia', '1993-01-05', 'rdogerty18@apple.com');
* insert into employee (id, name, birthday, email) values (46, 'Brion', '1998-05-24', 'bhawket19@1und1.de');
* insert into employee (id, name, birthday, email) values (47, 'Waldo', '1992-06-14', null);
* insert into employee (id, name, birthday, email) values (48, 'Althea', '1996-10-28', 'atickle1b@so-net.ne.jp');
* insert into employee (id, name, birthday, email) values (49, 'Lorita', '1991-11-30', 'lnayshe1c@examiner.com');
* insert into employee (id, name, birthday, email) values (50, 'Bran', null, 'bahren1d@icq.com');

3. Sütunların her birine göre diğer sütunları güncelleyecek 
   5 adet UPDATE işlemi yapalım.

* UPDATE author
* SET name = 'AAAB',
*     birtdhay = '1899-02-02',
*     email = 'aaa@bmail.com'
* WHERE id IN(1,2,3,4,5);

4. Sütunların her birine göre ilgili satırı silecek 5 adet 
   DELETE işlemi yapalım.

* DELETE FROM author
* WHERE id IN(6,7,8,9,10);



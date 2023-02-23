## PATIKA.DEV-SQL-HW-8

## [Patika.dev](https://www.patika.dev/tr)

---

<br>

> Create Database Commands

```sql

CREATE TABLE employee (
    id INTEGER PRIMARY KEY,
    name VARCHAR(50) NOT NULL,
    birthday DATE NOT NULL,
    email VARCHAR(100)
)

```

<br>

> Adding Data Commands

```sql

insert into employee (id, name, birthday, email) values (1, 'Dollie', '2018/06/24', 'dwoodbridge0@ca.gov');
insert into employee (id, name, birthday, email) values (2, 'Jacinthe', '2016/12/13', null);
insert into employee (id, name, birthday, email) values (3, 'Josiah', '2004/01/01', 'jpabst2@flickr.com');
insert into employee (id, name, birthday, email) values (4, 'Gearard', '2007/03/25', 'ggoodee3@chicagotribune.com');
insert into employee (id, name, birthday, email) values (5, 'Vicky', '2019/05/08', 'vfynn4@storify.com');
insert into employee (id, name, birthday, email) values (6, 'Celestia', '2019/11/01', 'chillam5@alibaba.com');
insert into employee (id, name, birthday, email) values (7, 'Homere', '1995/04/15', null);
insert into employee (id, name, birthday, email) values (8, 'Franchot', '2002/01/10', 'flilywhite7@who.int');
insert into employee (id, name, birthday, email) values (9, 'Breanne', '2020/12/23', 'bruecastle8@apache.org');
insert into employee (id, name, birthday, email) values (10, 'Ivory', '1994/08/02', 'ifreyn9@berkeley.edu');
insert into employee (id, name, birthday, email) values (11, 'King', '2017/01/16', 'kramalhoa@histats.com');
insert into employee (id, name, birthday, email) values (12, 'Martha', '1996/01/25', 'mdumelowb@rakuten.co.jp');
insert into employee (id, name, birthday, email) values (13, 'Britta', '2022/07/04', 'bmccarrollc@yelp.com');
insert into employee (id, name, birthday, email) values (14, 'Winnifred', '2007/08/23', 'wlukerd@dell.com');
insert into employee (id, name, birthday, email) values (15, 'Dredi', '2001/10/05', 'dokiee@smugmug.com');
insert into employee (id, name, birthday, email) values (16, 'Tanner', '2016/08/06', 'tmiltonwhitef@diigo.com');
insert into employee (id, name, birthday, email) values (17, 'Marji', '1997/05/01', 'mbunyang@multiply.com');
insert into employee (id, name, birthday, email) values (18, 'Corey', '2005/11/25', 'claleveeh@cpanel.net');
insert into employee (id, name, birthday, email) values (19, 'Jenny', '1993/03/08', 'jfliegeri@jalbum.net');
insert into employee (id, name, birthday, email) values (20, 'Merrill', '1993/06/03', null);
insert into employee (id, name, birthday, email) values (21, 'Merna', '2007/09/07', 'mcasollak@howstuffworks.com');
insert into employee (id, name, birthday, email) values (22, 'Kenon', '2002/01/27', 'khastinl@economist.com');
insert into employee (id, name, birthday, email) values (23, 'Inness', '1991/01/22', null);
insert into employee (id, name, birthday, email) values (24, 'Addy', '2010/09/12', 'alimeburnn@reference.com');
insert into employee (id, name, birthday, email) values (25, 'Emanuele', '2015/01/28', null);
insert into employee (id, name, birthday, email) values (26, 'Etty', '2018/12/08', 'ecanetp@blogger.com');
insert into employee (id, name, birthday, email) values (27, 'Llywellyn', '2002/09/16', 'lcellierq@hp.com');
insert into employee (id, name, birthday, email) values (28, 'Nataline', '1998/06/14', 'ngonsalor@bloglines.com');
insert into employee (id, name, birthday, email) values (29, 'Bartolomeo', '2004/01/04', 'bdaniauds@liveinternet.ru');
insert into employee (id, name, birthday, email) values (30, 'Alene', '2014/10/15', null);
insert into employee (id, name, birthday, email) values (31, 'Debi', '1992/10/03', 'dmettericku@imageshack.us');
insert into employee (id, name, birthday, email) values (32, 'Carrie', '2000/01/04', 'cclerkev@ox.ac.uk');
insert into employee (id, name, birthday, email) values (33, 'Halley', '2003/05/07', null);
insert into employee (id, name, birthday, email) values (34, 'Jaquith', '1993/06/22', 'jsawlex@opera.com');
insert into employee (id, name, birthday, email) values (35, 'Wyn', '2016/11/25', 'wclissoldy@techcrunch.com');
insert into employee (id, name, birthday, email) values (36, 'Friedrich', '1993/07/22', 'fdasz@blinklist.com');
insert into employee (id, name, birthday, email) values (37, 'Uri', '2016/07/19', 'uclutram10@blog.com');
insert into employee (id, name, birthday, email) values (38, 'Bernadina', '1997/08/29', 'bstoves11@fda.gov');
insert into employee (id, name, birthday, email) values (39, 'Stevy', '2007/08/15', 'srubinovici12@google.pl');
insert into employee (id, name, birthday, email) values (40, 'Lyndsay', '2019/01/08', 'ldain13@ox.ac.uk');
insert into employee (id, name, birthday, email) values (41, 'Ginger', '2008/05/18', 'grodenburg14@dailymail.co.uk');
insert into employee (id, name, birthday, email) values (42, 'Tedie', '2004/06/24', 'tjane15@themeforest.net');
insert into employee (id, name, birthday, email) values (43, 'Valentine', '2004/12/02', 'vlovegrove16@engadget.com');
insert into employee (id, name, birthday, email) values (44, 'Gretchen', '2014/06/17', null);
insert into employee (id, name, birthday, email) values (45, 'Cybill', '2017/05/31', 'cwhittier18@columbia.edu');
insert into employee (id, name, birthday, email) values (46, 'Bren', '1998/08/27', 'bshenton19@example.com');
insert into employee (id, name, birthday, email) values (47, 'Miquela', '2006/01/04', 'mdunbobbin1a@amazonaws.com');
insert into employee (id, name, birthday, email) values (48, 'Bond', '2014/09/21', 'bambrogini1b@spotify.com');
insert into employee (id, name, birthday, email) values (49, 'Reggie', '2013/04/15', 'rriccione1c@eepurl.com');
insert into employee (id, name, birthday, email) values (50, 'Sutherland', '2018/05/07', 'sault1d@wunderground.com');

```

<br>

> Update Commands
 
```sql

UPDATE employee
SET 
    name = 'Arda'
WHERE name = 'Sutherland'

```

```sql

UPDATE employee
SET
    birthday = '2000-10-06'
WHERE id = '50'

```

```sql

UPDATE employee
SET
    email = 'ardacankisakurek@gmail.com'
WHERE email = 'sault1d@wunderground.com'

```

```sql

UPDATE employee
SET
    email = ''
WHERE id < 10

```

```sql

UPDATE employee
SET 
    name = 'UPDATED'
WHERE name = 'Homere'

```

<br>

> Deleting Data Commands

```sql

DELETE FROM employee
WHERE name = 'UPDATED'

```

```sql

DELETE FROM employee
WHERE id < 10
RETURNING *

```

```sql

DELETE FROM employee
WHERE email = 'ardacankisakurek@gmail.com'
RETURNING *

```

```sql

DELETE FROM employee
WHERE id BETWEEN 25 AND 40

```

```sql

DELETE FROM employee
WHERE email = ''

```

<br>
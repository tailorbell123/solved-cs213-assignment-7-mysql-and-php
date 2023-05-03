Download Link: https://assignmentchef.com/product/solved-cs213-assignment-7-mysql-and-php
<br>
<span class="kksr-muted">Rate this product</span>

1.0) Create a database called ‘publications’.This database will have two tables called ‘authors’ and ‘titles’.(you can sample.txt for raw data).

Table ‘authors’ will have following schema:

+———+————–+——+—–+———+——-+ |Field |Type |Null|Key|Default|Extra| +———+————–+——+—–+———+——-+| author | varchar(120) | YES | | NOT NULL| | | publisher| varchar(30) | YES | | NULL | | +———+————–+——+—–+———+——-


Table ‘titles’ will have following schema: +——-+————–+——+—–+———+——-+ | Field | Type | Null | Key | Default | Extra | +——-+————–+——+—–+———+——-+ | title | varchar(120) | YES | | NOT NULL| | | author| varchar(120) | YES | | NULL | | |year |smallint(6) |YES | |NULL | | +——-+————–+——+—–+———+——-


Write a PHP program in which you communicate with this database and have following functionalities:

1.1) Display all the records in both the tables.1.2) Adding a record (available for both the tables). 1.3) Deleting a record (available for both the tables). 1.4) Updating year of publication for a given title.

It might be possible that user might submit a substring of title. 1.5) Given a book find its author and year of publication.

It might be possible that user might submit a substring in the book. 1.6) Given a publisher– find all the books (names of the books)

which authors from that publisher have published, publication year.

( i.e., publisher wise listing of books, authors along with publication year). 1.7) When you are updating/adding please do the data type check
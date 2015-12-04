# Designing Databases

A database needs to be reliable, consistent and have a structure that suits the data you collect. A database is stored in a
a format such as a **CSV** file and saved on a **hard drive**.

Databases are persistent, which means that the structure is fixed in a place. The fields and data values are set so that it is
easy to add information and build a **database** without changing the structure. If you create a program which needs to access a
database, the database needs to be persistent so that records can be modified while the program runs.

When designing a database:

* Decide what the structure will be before you start adding data. Because it's dificult to change structure once it's been set
* in place.
 
Data not organised - dificult to work with.

For example, it's hard to make sense of this data which contains data from an address book:

| Ash           | Nia          | becky@bbc.com | 02398 374927  |
| 02298 837492  | James        | Irfan         | Becky         |
| james@bbc.com | 04972 048204 | Mo            | irfan@bbc.com |
| 04973 048204  | nia@bbc.com  | Email         | Parker        |       

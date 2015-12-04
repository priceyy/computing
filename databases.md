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
|---------------|--------------|---------------|---------------|
| 02298 837492  | James        | Irfan         | Becky         |
| james@bbc.com | 04972 048204 | Mo            | irfan@bbc.com |
| 04973 048204  | nia@bbc.com  | Email         | Parker        |  

| ID | Name  | HomePhone    | Mobile        | Email         |
|:---|-------|--------------|---------------|---------------|
| 1  | Irfan | 02298 837492 | 0888 87492    | irfan@bbc.com |
| 2  | James | 02398 374927 | 098284 278213 | james@bbc.com |
| 3  | Becky | 03472 827492 | 098252 472911 | becky@bbc.com |
| 4  | Nia   | 04972 048204 | 046482 472912 | nia@bbc.com   |

# deltaX_rec
This project deals with the Movie Application which allows the user to view, Add,Edit and delete the movie details which exist in the database.This entire Application is developed in ASP.NET using visual studio 2015.Design part is done using CSS and database server used is SQL server.

 Master  page consits of already added details which has two options edit and add, based on the user input the page redirects to Editpage or  Viewpage. In Edit page I have given a form to be filled where all the fields are mandatory, As soon as user edits the data and submit it the changes are reflected in master page. On the add button click the page redirects to Add database webpage where once again a form needs to be filled, If all the data entered is already there in database it wont create a duplicate row, throws an error.
 

## DATABASE
Database consist of only one table *MOVIE*
### Movie
Consits of the movie data that user enters

#### Columns:

|       Name         |Type                           |Primary key                  |
|-----------------|-------------------------------|-----------------------------|
|id                |int                       |yes                        |     
|MovieName         |varchar                      |no                         |
|Release date      |datetime                     |no                         |
|Producer          |varchar                      |no                         |
|Actor             |varchar                      |no                         |

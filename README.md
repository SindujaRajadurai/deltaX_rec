# deltaX_rec
This project deals with the Movie Application which allows the user to view, Add,Edit and delete the movie details which exist in the database.This entire Application is developed in ASP.NET using visual studio 2015.Design part is done using CSS and database server used is SQL server.

 # Functioning 
 Master page consists of the movie information on viewmode and two options edit and add, based on the user input the page redirects to Editpage or  Addpage. Editpage is to edit an existing record, If user edits the data and submit, the changes will be reflected in the master page. In the same way If user tries to add a record, the page redirects to Addpage where user can add a new movie detail.In both the cases all the fields are mandatory.

## DATABASE
Database consist of only one table *MOVIE*.
### Movie
Consits of the movie data that user enters.

#### Columns:

|       Name         |Type                           |Primary key                  |
|-----------------|-------------------------------|-----------------------------|
|id                |int                       |yes                        |     
|MovieName         |varchar                      |no                         |
|Release date      |datetime                     |no                         |
|Producer          |varchar                      |no                         |
|Actor             |varchar                      |no                         |

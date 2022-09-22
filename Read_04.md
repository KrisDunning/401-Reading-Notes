
[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 04 - Data Modeling

## Discussion Questions

### nosql vs sql

1) What type of database is the best fit for the complex query intensive environment?
> SQL databases are the best fit for a complex query intensive environment.

2) What type of database is the best fit for hierarchical data storage?
> NoSQL databases are the best fit for a hierarchical data storage. 

3) Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
> If your database is an old west horse and wagon, to upgrade or scale it's ability to pull a load, SQL would be swapping the horse with a big, heavy draft horse. NoSQL would be adding more of the basic horses.

### sql modeling techniques

1) Among data tables, what is a one-to-many relationship and how do we “relate” them?
> When one entry in a table can be related to more than one entries in another table. We use a "foreign key" to relate them to other tables "primary keys".

2) Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
> Create a diagram

3) Explain the difference between a primary and foreign key.
> Primary keys uniquely identify a row in a table. Foreign keys are a column that match another tables primary keys.

### sql vs nosql

1) How do we treat keywords and parameters differently in SQL syntax?
> SQL keywords are written in all capitalization. Parameters are lower case. 

2) Define normalization within the context of schemas and data.
> Normalization means to take the data and the schemas and make sure that the fields we create for the schemas can fit our required data and that the data can be used to fit our schema. 

3) Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
> one-to-one is if I had one car, I would be one table and the car would be one. If I had a car and a motorcyle, I would be one table and the car and motorcycle would be tables. If me and my wife both owned 2 cars, I would be a table, my wife would be a table, each car would be seperate table and we all would be related to each other.

## Things I want to know more about

How to better conceptualize data table relations. I just need some hands on practice. Which it sounds like today should be happening.

-----

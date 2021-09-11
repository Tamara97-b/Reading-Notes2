#  SQL AND NoSQL
## What kind of data is a good fit for an SQL database?
If your data is highly structured and associations among the program entities are clearly defined (for instance, if you are developing a point of sale system where you need to store customer orders and product records), conventional SQL based databases are the best fit.

## What kind of data is a good fit a NoSQL database?
High velocity read/write with no frequent updates. High performance and scalability. No complex queries involving multiple keys or joins.

## Which type of database is best for hierarchical data storage?
The type of data to be stored : SQL databases are not suitable for hierarchical data storage. However, the NoSQL database is better suited for hierarchical data storage because it follows the key-value pair method or graph method
## Which type of database is best for scalability?
The clear winner with over 1/3 of multiple database type use is the combination of MySQL and MongoDB. While MongoDB is often considered an alternative to MySQL, the two databases do work well together when properly designed. The second most popular combination was MySQL and PostgreSQL together.

## What does SQL stand for?
SQL (pronounced "ess-que-el") stands for Structured Query Language. SQL is used to communicate with a database. According to ANSI (American National Standards Institute), it is the standard language for relational database management systems.
## What is a realational database?
A relational database is a type of database that stores and provides access to data points that are related to one another. Relational databases are based on the relational model, an intuitive, straightforward way of representing data in tables. In a relational database, each row in the table is a record with a unique ID called the key. The columns of the table hold attributes of the data, and each record usually has a value for each attribute, making it easy to establish the relationships among data points.
## What type of structure does a relational database work with?
The relational model means that the logical data structures—the data tables, views, and indexes—are separate from the physical storage structures. This separation means that database administrators can manage physical data storage without affecting access to that data as a logical structure.
## What is a ‘schema’?
The database schema is its structure described in a formal language supported by the database management system (DBMS). The term "schema" refers to the organization of data as a blueprint of how the database is constructed (divided into database tables in the case of relational databases). The formal definition of a database schema is a set of formulas (sentences) called integrity constraints imposed on a database.[citation needed] These integrity constraints ensure compatibility between parts of the schema. All constraints are expressible in the same language. A database can be considered a structure in realization of the database language.[1] The states of a created conceptual schema are transformed into an explicit mapping, the database schema. This describes how real-world entities are modeled in the database.
## What is a NoSQL database?
NoSQL databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.


## Howo does it work?
NoSQL is an approach to databases that represents a shift away from traditional relational database management systems (RDBMS). ... Relational databases rely on tables, columns, rows, or schemas to organize and retrieve data. In contrast, NoSQL databases do not rely on these structures and use more flexible data models.
## What is inside of a Mongo database?
MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections. A database stores one or more collections of documents.
## Which is more flexible - SQL or MongoDB? and why.
While MongoDB is more flexible and ensures high and diverse data availability, a SQL Database operates with the ACID (Atomicity, Consistency, Isolation, and Durability) properties and ensures greater reliability of transactions.
## What is the disadvantage of a NoSQL database?
Disadvantages. NoSQL databases don't have the reliability functions which Relational Databases have (basically don't support ACID). This also means that NoSQL databases offer consistency in performance and scalability.
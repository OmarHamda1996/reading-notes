### Database Types and Relationships

- **What type of database is the best fit for the complex query intensive environment?**

SQL databases, also known as Relational Databases (RDBMS), are table-based databases, while NoSQL databases are non-relational or distributed databases. SQL databases store data in the form of tables with rows, while NoSQL databases can store data as documents, key-value pairs, graph structures, or wide-column stores. SQL databases have a predefined schema, while NoSQL databases have a dynamic schema that allows for unstructured data.

- **What type of database is the best fit for hierarchical data storage?**

NoSQL databases are generally considered a better fit for hierarchical data storage. This is because NoSQL databases, especially document-oriented databases, can store data in a flexible and schema-less manner, allowing for the representation of hierarchical structures.

- **Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**

Imagine SQL databases like a big, powerful machine that you keep upgrading with better and faster components (CPU, RAM, storage) to handle more load. NoSQL databases, on the other hand, are like a group of smaller machines working together, with each machine handling a portion of the data and load.

### Data Modeling and Relationships

- **Among data tables, what is a one-to-many relationship and how do we "relate" them?**

In a one-to-many relationship, one record in a table can have multiple related records in another table. To relate them, we use a foreign key in the table that represents the "many" side. The foreign key refers to the primary key of the table representing the "one" side, creating a connection between the two tables.

- **Prior to designing your relational database, it might be useful to create a diagram of the database tables and their relationships.**

Prior to designing a relational database, it's useful to create a diagram of the tables and their relationships. This diagram helps visualize the structure and connections of the database.

- **Explain the difference between a primary and foreign key.**

A primary key is a unique identifier for each record in a table. It ensures each record is uniquely identified. A foreign key, on the other hand, is a field in one table that refers to the primary key in another table. It establishes a relationship between the tables by linking records based on their key values.

- **How do we treat keywords and parameters differently in SQL syntax?**

In SQL syntax, keywords have predefined meanings and are used for specific operations. They are part of the SQL language itself. Parameters, on the other hand, are values passed into SQL statements to customize their behavior or provide dynamic values. Parameters can be used for filtering data, defining sorting criteria, or specifying conditions in SQL queries.

- **Define normalization within the context of schemas and data.**

Normalization is the process of organizing data in a database schema to reduce redundancy and improve data integrity. It involves breaking down data into smaller, logical units and establishing relationships between them. Normalization helps eliminate data duplication, ensure consistency, and make the database more efficient and maintainable.

- **Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

    - One-to-many relationship: One record in a table can be related to multiple records in another table, like a parent having multiple children.
    - Many-to-many relationship: Multiple records in one table can be associated with multiple records in another table. It requires a join table to establish the relationship, acting as a bridge between the two tables. It's like a many-to-many connection between two entities where both sides can

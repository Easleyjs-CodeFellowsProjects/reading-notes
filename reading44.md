# Reading Notes (401) Reading 04 - easleyjs

SQL vs NoSQL

## Things I want to know more about

I'd be curious to know more about the ideal use cases for a NoSQL db.

## Questions

**What type of database is the best fit for the complex query intensive environment?**

A relational db

**What type of database is the best fit for hierarchical data storage?**

A NoSQL db

**Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**

To accomodate for data and/or requests, you would need to give more resources (CPU, memory, etc.) to scale up a relational db. With a NoSQL db, you'd add more db servers so that the load was distributed between those.

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

One-to-many is when a single record can have many corresponding records in a related table, like a single customer (record) having many orders. Tables are related by their primary and foreign keys.

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

Draw/design a database diagram.

**Explain the difference between a primary and foreign key.**

A primary key is the key on the table itself that identifies its own unique records. A foreign key is a key that corresponds to the primary key of another table.

**How do we treat keywords and parameters differently in SQL syntax?**

Queries are structured in a way that keywords are in specific positions, with parameters coming after them similar to functions in JS.

**Define normalization within the context of schemas and data.**

Normalizing is structuring the data so that it's arranged into logical tables where all rows are unique and are used by other tables via relation. One schema should not contain two different types of data joined together.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

- One-to-one: Individual rows in a table correspond and are related to one, or zero rows in another table.

- One-to-many: Individual rows in a table correspond to zero, or up to many rows in another table.

- Many-to-many: Zero to many rows in a table can correspond to zero to many rows in another table.

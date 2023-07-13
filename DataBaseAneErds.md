# Introduction to Databases and ERDs

## What is a Schema?

In a database context, a schema refers to a logical container or structure that organizes and defines the database objects, such as tables, views, indexes, procedures, and functions. It acts as a blueprint or design for the overall database structure.
A database schema defines the relationships and attributes of the database objects within a database system. It provides a framework for organizing and categorizing data, ensuring consistency, integrity, and security. It determines the logical structure and organization of the database, including the tables, columns, data types, constraints, and relationships between tables.

## Why do we use them?

Organization and Structure: Schemas provide a way to organize and structure the database objects, such as tables, views, and procedures, into logical groups. This organization helps in managing and maintaining a large database system, making it easier to locate and work with specific objects.

Data Isolation: Schemas provide a level of data isolation and separation. Different schemas can be created to hold related objects for different applications, departments, or users. This separation helps in managing access control and security, as each schema can have its own permissions and restrictions on who can access or modify the data within it.

Security and Access Control: Schemas allow for granular control over access to the database objects. By assigning different permissions to schemas, you can restrict or grant access to specific users or roles. This ensures that sensitive data is only accessible to authorized individuals or applications.

## What do they look like?
PostgreSQL

MySQL

Oracle

## What is a Primary Key?
A primary key is a unique identifier for a record or row in a database table. It is a column or a set of columns that uniquely identifies each row in the table. The primary key enforces the entity integrity constraint, which ensures that there are no duplicate or null values in the primary key column

## What is a Foreign Key?
A foreign key is a column or a set of columns in a database table that establishes a link or relationship between that table and another table. It represents a reference to a primary key in another table, creating a relationship between the two tables. The foreign key constraint ensures data integrity and enforces referential integrity between related tables

## What is a Composite Key?
A composite key, also known as a composite primary key, is a key that consists of multiple columns in a database table. Unlike a simple or single-column primary key, a composite key uses a combination of two or more columns to uniquely identify each row in the table. Together, the values in the composite key must be unique within the table.

## How are they different? When do you use 1 over the others?
A primary key and a composite key are both used to uniquely identify records in a database table. However, they differ in terms of their composition and usage:

Primary Key:
- A primary key is a single column or a minimal set of columns that uniquely identifies each record in a table.
- It enforces the entity integrity constraint, ensuring uniqueness and non-nullability of the key column(s).
- A primary key is often used as a default identifier for a table when there is a single column that can uniquely identify each record.
- It simplifies data retrieval and referencing in relationships by providing a simple, single-value identifier for each record.
- Primary keys are typically used when a single column or a minimal combination of columns can uniquely identify records.

Composite Key:
- A composite key is a key that consists of two or more columns in a table, forming a combined value that uniquely identifies each record.
- It is used when a single column cannot uniquely identify records, but the combination of multiple columns can.
- Composite keys are often used to represent more complex relationships and identification requirements in the data model.
- They allow for greater specificity and precision in identifying records by considering multiple attribute values together.
- Composite keys are typically used when a combination of multiple columns is needed to uniquely identify records, such as in cases where no single column can serve as a unique identifier.

In general, the choice between using a primary key or a composite key depends on the specific requirements of the data model and the relationships between tables. Here are some considerations:

- Primary keys are simpler and more straightforward to work with when a single column can uniquely identify records. They are commonly used in most database designs and are suitable for many situations.
- Composite keys are used when a single column cannot provide unique identification, requiring a combination of multiple columns. They are suitable when the uniqueness of a record depends on multiple attributes and their combinations.

It is important to note that while composite keys can provide more specificity, they can also introduce complexity in terms of querying and managing relationships. Therefore, it is generally recommended to use composite keys when necessary, but to keep them as simple and minimal as possible to maintain ease of use and readability.

# DBMS

Relationships in a relational database represent associations or connections between tables based on common fields or attributes. These relationships define how the records in different tables are related to each other.

1. One-to-One Relationship:
   In a one-to-one relationship, one record in a table is associated with only one record in another table, and vice versa. Each record in both tables has a unique and exclusive relationship with the corresponding record in the other table. One-to-one relationships are not very common but are used in situations where data needs to be split into separate tables for specific reasons, such as normalization or security purposes.

2. Many-to-Many Relationship:
   In a many-to-many relationship, multiple records in one table can be associated with multiple records in another table. This relationship requires the use of a junction or bridge table that connects the two tables, typically containing foreign keys from both tables. The junction table allows for the representation of all the possible combinations or associations between records in the two tables. Many-to-many relationships are commonly used when there is a need to represent complex, multi-faceted relationships between entities.

3. One-to-Many Relationship (or Many-to-One Relationship):
   In a one-to-many relationship, one record in a table can be associated with multiple records in another table, but each record in the second table is associated with only one record in the first table. This relationship is also known as a "parent-child" relationship. The "one" side of the relationship is represented by a primary key in the parent table, which is referenced as a foreign key in the child table. One-to-many relationships are widely used in database designs to represent hierarchies, such as customers and orders or students and courses.


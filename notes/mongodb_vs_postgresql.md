# MongoDB vs PostgreSQL

Comparison between MongoDB and PostgreSQL.

---

## MongoDB

Database Type:

* NoSQL
* Document Database

Data Structure:

* JSON-like documents

Schema:

* Flexible

Example:

```json
{
"name":"Sanjana",
"age":24,
"course":"FSD"
}
```

Advantages:

* Flexible schema
* Fast development
* Easy scaling
* Good for rapidly changing data

Common Use Cases:

* Social media
* Chat applications
* Content management
* Product catalogs

---

## PostgreSQL

Database Type:

* Relational Database (SQL)

Data Structure:

* Tables

Schema:

* Structured

Example:

Students

| id | name    | age |
| -- | ------- | --- |
| 1  | Sanjana | 24  |

Advantages:

* Strong relationships
* Complex joins
* Excellent transactions
* Better for structured systems

Common Use Cases:

* Banking
* ERP
* HR systems
* Inventory
* Enterprise applications

---

## Example Comparison

MongoDB

```json
{
"name":"Sanjana",

"course":{
"name":"FSD"
}
}
```

PostgreSQL

students

| id | name    |
| -- | ------- |
| 1  | Sanjana |

courses

| student_id | course |
| ---------- | ------ |
| 1          | FSD    |

---

## Summary

MongoDB:

* Flexible
* Document based
* Faster for changing data

PostgreSQL:

* Structured
* Relational
* Better for complex business systems

---

## Learning Path

Completed:

✔ PostgreSQL Basics
✔ MongoDB Foundations

Next:

Node.js
Express
MongoDB
Mongoose
REST API

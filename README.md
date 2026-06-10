# MongoDB Learning 🚀

Learning MongoDB through hands-on practice using MongoDB Compass and MongoDB Shell (mongosh).

This repository contains practical exercises and notes covering MongoDB fundamentals for backend and full stack development.

---

## Topics Covered

### CRUD Operations

* Create → `insertOne()`
* Read → `find()`
* Update → `updateOne()`
* Delete → `deleteOne()`

### Query Operators

* `$gt`
* `$gte`
* `$lt`
* `$lte`

### Aggregation

* `$group`
* `$sum`

### Indexing

* `createIndex()`
* `getIndexes()`

### Data Modeling

* Embedded Documents
* References

---

## Repository Structure

```text
mongodb-learning/
│
├── README.md
│
├── queries/
│   ├── 01_create_insert.md
│   ├── 02_read_find.md
│   ├── 03_update.md
│   ├── 04_delete.md
│   ├── 05_aggregation.md
│   ├── 06_indexing.md
│   ├── 07_embedded_documents.md
│   └── 08_references.md
│
├── notes/
│   ├── embedded_vs_reference.md
│   └── mongodb_vs_postgresql.md
│
└── screenshots/
```

---

## Database Used

```text
studentDB
```

Collection:

```text
students
```

---

## Sample Queries

Find all documents

```javascript
db.students.find()
```

Find students older than 22

```javascript
db.students.find({
 age:{
  $gt:22
 }
})
```

Aggregation

```javascript
db.students.aggregate([
{
 $group:{
  _id:null,
  total:{
   $sum:1
  }
 }
}
])
```

Create index

```javascript
db.students.createIndex({
 name:1
})
```

---

## Tools Used

* MongoDB Server
* MongoDB Compass
* MongoDB Shell (mongosh)
* GitHub

---

## Learning Outcome

After completing this repository:

* Understand MongoDB document structure
* Perform CRUD operations
* Work with aggregations
* Use indexing
* Compare Embedded vs Reference modeling
* Practice terminal-based MongoDB workflow

---

## Next Step

Node.js → Express → MongoDB → Mongoose → REST API

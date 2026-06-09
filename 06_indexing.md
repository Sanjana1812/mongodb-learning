# Indexing

Create index on name

```javascript
db.students.createIndex({
 name:1
})
```

Show indexes

```javascript
db.students.getIndexes()
```

Create compound index

```javascript
db.students.createIndex({
 name:1,
 age:-1
})
```

Remove index

```javascript
db.students.dropIndex(
"name_1"
)
```


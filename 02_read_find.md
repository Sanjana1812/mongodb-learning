# Read / Find

Show all documents

```javascript
db.students.find()
```

Find by name

```javascript
db.students.find({
 name:"Rahul"
})
```

Find age greater than 22

```javascript
db.students.find({
 age:{$gt:22}
})
```

Find age less than 25

```javascript
db.students.find({
 age:{$lt:25}
})
```

Find exact age

```javascript
db.students.find({
 age:24
})
```


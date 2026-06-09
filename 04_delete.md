# Delete

Delete one document

```javascript
db.students.deleteOne({
 name:"Rahul"
})
```

Delete multiple

```javascript
db.students.deleteMany({
 age:{$gt:30}
})
```

Verify deletion

```javascript
db.students.find()
```


# Update

Update one document

```javascript
db.students.updateOne(
 {name:"Rahul"},
 {
  $set:{
   age:25
  }
 }
)
```

Verify update

```javascript
db.students.find()
```

Update course

```javascript
db.students.updateOne(
 {name:"Sanjana"},
 {
  $set:{
   course:"Full Stack Development"
  }
 }
)
```


# References

Create student

```javascript
db.students.insertOne({

_id:1,

name:"Sanjana"

})
```

Create course

```javascript
db.courses.insertOne({

student_id:1,

course:"FSD"

})
```

Show students

```javascript
db.students.find()
```

Show courses

```javascript
db.courses.find()
```

Find course for student

```javascript
db.courses.find({

student_id:1

})
```

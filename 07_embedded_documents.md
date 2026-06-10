# Embedded Documents

Create embedded document

```javascript
db.students.insertOne({

name:"Sanjana",

course:{
name:"Full Stack Development",
duration:"6 months"
},

address:{
city:"Hyderabad",
pin:500001
}

})
```

Show data

```javascript
db.students.find()
```

Find embedded field

```javascript
db.students.find({
"course.name":
"Full Stack Development"
})
```

Update embedded field

```javascript
db.students.updateOne(

{name:"Sanjana"},

{
$set:{
"address.city":
"Bangalore"
}
}

)
```

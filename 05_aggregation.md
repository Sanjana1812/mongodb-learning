# Aggregation

Count documents

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


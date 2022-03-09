# javascript_interview_important_questions

## What is prototype ?
### Prototype is an object which is associated with functions and object's of javascript. Which is used to add properties of objects.
### Functions properties can be accessed by using keyword prototype and Object's properties can be accessed by __proto__ keyword.
```function Stud(){
    this.name = "Siddharth",
    this.age = 11
}

Stud.prototype.address = "Manpur gaya"
var Obj1 = new Stud()
console.log(Obj1.address);
Obj1.__proto__.district = "Gaya"
console.log(Obj1.district);```
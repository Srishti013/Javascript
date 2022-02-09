## Declaration, Accessing Properties of Objects and Modifiction
```javascript

// declaration
const dog = {
  breed: "pitbull",
  color: "brown",
  name: "Coco"
};  // The semicolon in the end is optional


// Accessing
console.log(dog.breed);  // "pitbull"
console.log(dog.color); // "brown"
console.log(dog.name);  // "Coco



// Modifiction
dog.name = "Tom";



// Adding new properties
dog.age = 9;
```

## Methods

```javascript
const dog = {
  breed: "pitbull",
  color: "brown",
  name: "Coco"
  
 describe() {
    return `${this.name} is a ${this.breed} and is ${this.color} in color`;
  },
  
  Bark()
  {
     console.log("Woof!");
   }
};

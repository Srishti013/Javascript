## Declaration

```javascript
class MyClass {
  constructor(param1, param2, ...) {
    this.property1 = param1;
    this.property2 = param2;
    // ...
  }
  method1(/* ... */) {
    // ...
  }
  method2(/* ... */) {
    // ...
  }
  // ...
}
```

## Object oriented Model

```javascript

// Objects can inherit properties of other objects too without the use of classes

const MyOb =
{
    prop1 : 5,
    hello()
    {
        console.log("hello");
     }
 };
 
 const secObj = Object.create(MyOb);
 console.log(secObj.prop1); //5
}
```

## Declaration
```javascript

// These arrays can store various types of elements together
const Myarray = ["element1","element2",3,4];

```

## Obtaining Array Size

```javascript

console.log(Myarray.length); // 4
```

## Accessing elements


```javascript

// For loop
for(let i=0;i<Myarray.length;i++)
{
   console.log(Myarray[i]);
}



// forEach 

Myarray.forEach(element => {
  console.log(element);
});



// For-of
for(const element of Myarray)
{
    console.log(element);
}
 ```

## Adding an element

```javascript

// To add element at the end of the array
Myarray.push(5);

//To add element at the beginnning
Myarray.unshift(0);

```

## Removing an element

```javascript

// To remove the last element
Myarray.pop() // Removes 5

// To remove 2 elements starting from index 0
Myarray.splice(0,2) // Removes 0,element1
```

## map() Method

```javascript

const num = [1,2,3,4];
const sq = num.map( n => n**2); // sq = [1,4,9,16]

```

## filter Method

```javascript

const num = [1,2,3,4];
const greaterThan2 = num.filter( n => n>2); // greaterThan2 = [3,4]

```

## reduce Method

```javascript

const num = [1,2,3,4];
const sum = num.reduce( (acc,value) => acc+value,0); // sum = 10

```

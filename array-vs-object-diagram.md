# JavaScript: Array vs Object Diagram

![diagram](https://jsohndata.s3.amazonaws.com/images/github-gist/array-compared-to-object-diagram.webp)

## Explaination
<img src="https://jsohndata.s3.amazonaws.com/images/github-gist/legend-letter-a.webp" width="25" /> Best practice to use the keys as string.

<br>

<img src="https://jsohndata.s3.amazonaws.com/images/github-gist/legend-letter-b.webp" width="25" />  `Dot Notation` is used when you know the exact name of the key to access the property.

```
const dogName = myFavDog.name
```

<br>

`Bracket Notation` is used when you know the exact name of the key or using an expression to access the property.

```
const keyName = "breed";
const dogBreed = myFavDog[keyName];

or...

const dogBreed = myFavDog["breed"];
```

<br>
# Doc: JavaScript - Array vs Object

## Both objects and arrays are considered “special” in JavaScript. 

`Arrays`: Special type of variable that is also mutable and can also be used to store a list of values

`Objects`: Special data type that is mutable and can be used to store a collection of data (rather than just a single value)

`One Sentence`: Objects represent “things” with characteristics (aka properties), while arrays create and store lists of data in a single variable. Both dot and bracket notation allow us to access, add, change, and remove items from an object, while zero-based indexing and a variety of built-in methods let us access and alter items in an array.

## Array
We use arrays whenever we want to create and store a list of multiple items in a single variable. Arrays are especially useful when creating ordered collections where items in the collection can be accessed by their numerical position in the list. Just as object properties can store values of any primitive data type (as well as an array or another object), so too can arrays consist of strings, numbers, booleans, objects, or even other arrays.

## Object
Objects are used to represent a “thing” in your code. That could be a person, a car, a building, a book, a character in a game — basically anything that is made up or can be defined by a set of characteristics. In objects, these characteristics are called properties that consist of a key and a value.

Properties in objects can be accessed, added, changed, and removed by using either dot or bracket notation.






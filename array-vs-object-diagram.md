# Doc: Javascript - Array vs Object Diagram

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




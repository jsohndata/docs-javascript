# Doc: String Methods - JavaScript

There are about 30 different string methods. Here are some I find useful to know.

## `charAt()`
Returns the character at the specified index.

```
const str = "Hello, World!";
const char = str.charAt(0)
console.log(char); // Outputs H
```

<br>

## `substring()`
Extract a portion of a string and return it as a new string.

```
const str = "Hello, World!";
const subStr = str.substring(0, 5);
console.log(char); // Outputs "Hello"
```

If you omit the second parameter, this will extract all the characters from the starting index to the end of the string.
```
const str = "Hello, World!";
const subStr = str.substring(7);
console.log(char); // Outputs "world!"
```

<br>

## `repeat()`
eturns a new string by concatenating the original string a specified number of times.
```
const str = 'Hello, World! '
console.log(str.repeat(3))

// Hello, World! Hello, World! Hello, World!
```

<br>

# Length, Property not a Method

## `length`
 
Built-in property of JavaScript strings that returns the number of characters in a string.

```
const str = "Hello, World!";
const len = str.length;
console.log(char); // Outputs 13
```


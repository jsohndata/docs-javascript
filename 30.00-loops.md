# JavaScript: Loop

In JavaScript, loops are used to execute a block of code repeatedly.

## Common Loop

### For
The `For` loop is used to iterate over a block of code a specified number of times.


Synatx
```
for (initialization; condition; increment/decrement) {
  // code to be executed
}
```

Example
```
for (let i = 0; i < 5; i++) {
  console.log(i);
}

--- Output ---
0
1
2
3
4
```

<br>

### While

The `while` loop is used to execute a block of code as long as the specified condition is true.

```
while (condition) {
  // block of code to be executed
}
```

## Other For Loops

### For...In
`for...in` loop: This loop is used to iterate over the properties of an object.

```
for (variable in object) {
  // block of code to be executed
}
````

<br>

### For...Of
`for...of` This loop is used to iterate over iterable objects such as arrays, strings, and maps.


<br>

### Do While
`do...while` loop is similar to the while loop, but the block of code is executed at least once before the condition is checked.

```
do {
  // block of code to be executed
} while (condition);
```
<br>

```
/*
Count down to 10 and blast off!!
*/

function initiateBlastOff () {
  
  for (let i = 10; i >= 1; i --) {
      console.log(`Countdown in ... ${i}`);

      if (i === 1) {
        console.log(`🚀 Blast off!!!!`);
    }
  }
}

initiateBlastOff()
```

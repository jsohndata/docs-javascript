# Doc: JavaScript - Condition: If, Switch, Ternary

## If Statment
Block of code to be executed, when the condition in the parenthesis are true.

```
const pet = "dog";

if (pet === "dog") {
  console.log("bark"); 
}
```

<br>

## If-Else Statment
If the condition for the first block of code is false, then the else block will be executed.

```
const pet = "dog";

if (pet === "dog) {
  console.log("bark");
} else {
  console.log("meow);
}
```

<br>


## Else-If Statement

if statement to add additional conditions to the same block of code.
```
const pet = "dog";
let sound;

if (pet === "dog") {
  sound = "bark";
} else if (pet === "cat") {
  sound = "meow";
} else {
  sound = "hello";
}

console.log("sound:", sound);
```

***Question***
>Why is sound `let` not `const`?

The variable `sound` is declared using `let` instead of `const` because its value may change later in the code, depending on the condition in the `if statement`. When you declare a variable using `const`, its value cannot be changed, but with `let` it can.

<br>

## Switch
```
const pet = "dog";
let sound;

switch (pet) {
  case "dog":
    sound = "bark";
    break;

  case "cat":
    sound = "meow";
    break;
  
  default:
    sound = "hello!";
    break;
}

console.log("sound:", sound);
```
>Why is sound `let` not `const`?

`sound` is declared using `let` instead of `const` because its value can change based on the case matched in the `switch statement`. `let` allows the value of the variable to be reassigned, while `const` does not.

<br>

## Ternary
The ternary operator is a shorthand way of writing an if...else statement in JavaScript. It takes three operands: a condition, a value if the condition is true, and a value if the condition is false.
```
const pet = "dog"
let sound;

const sound = (pet === "dog") ? sound = "bark" : sound = "meow";
```
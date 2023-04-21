# Doc: Javascript - Functions: Naming Convention, Parameter and Argument.

## Function Naming Convention
1. `Use descriptive and concise names`: Name your functions according to their purpose, so that it's easy to understand what they do. Keep the function names concise, but not too short that they become ambiguous.
2. `Use camelCase`: Use camelCase for function names, starting with a lowercase letter. For example, `getUserData()`.
3. `Use verbs`: Use verbs to describe what the function does. For example, calculateTotal().
4. `Use meaningful variable names`: Use meaningful names for the parameters passed to the function.
5. `Use consistent naming conventions`: Use consistent naming conventions across your codebase. If you're working with a team, agree on a set of naming conventions to use.

<br>

## Sample of Function and Parameter Names
* `getUserInfo(userId)`: Retrieves user information from an API.
* `calculateDistance(x1, y1)`: Calculates the distance between two points.
* `generateRandomNumber(minNumber, maxNumber)`: Generates a random number.
* `convertToUpperCase(text)`: Converts a string to uppercase letters.
* `toggleVisibility()`: Toggles the visibility.

<br>

## Difference between Parameter and Argument
* `Parameter`: A named variable that is part of a function's definition. It is used to define what type of data the function expects to receive as input. 

* `Argument`: A value that is passed or provided to a function. When the function is invoked the arguments are passed in parentheses after the function name.

* `One sentence`: The parameter is a variable in the function that represents the expected input value, while the argument is the actual value that is passed into the function when it is called.

<br>

## Variations

* `Function Decloration`

Function declared by using the function keyword.
```
function getUserId(){
  //execute
}
```

* `Function Expression`

Using anonymous function (function without a name) as a value.
```
const eatFood = function(whatFood) {
  //execute
} 
```

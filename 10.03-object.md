# JavaScript: Object
Objects in programming can be a combination of variables, functions, and data structures.

<br>

## Property: key, value pair 
* key = assigned
* value = string, int, object, array, method

    ```
    const person = {
        firstName: "Jiho", // key => firstName
        lastName: "Sohn", // key => lasttName
        age: 47    // key => age
    }
    ```
<br>

## Access: Dot Notation
* `const personFName = person.firstName`
* `const personLName = person.lastName`

## Access: Bracket Notation
* `person['firstName']`
* `person['lastName']`

<br>

## Mutate Object
* Mutate properties
<br> `objectName.keyName = newValue`

* Add new properties
<br> `objectName.newKeyName = newValue`

* Delete properties
<br> `delete objectName.keyName`
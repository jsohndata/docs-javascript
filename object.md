# JavaScript: Object
Objects in programming can be a combination of variables, functions, and data structures.

<br>

## Property: key, value pair 
* key = assigned
* value = property value = string, int, object, array, method */

```
const person = {
    firstName: "Jiho", // key => firstName
    lastName: "Sohn", // key => lasttName
    age: 47    // key => age
}
```
<br>

## Access 
* const personFName = person.firstName  || person['firstName']
* const personLName = person.lastName || person['lastName']
* const personaAge = person.age || person['age']


## Mutate Object
`mutate properties`
objectName.keyName = newValue

`Add new properties `
objectName.newKeyName = newValue

`Delete properties`
delete objectName.keyName
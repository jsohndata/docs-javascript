# JavaScript: Array

An array is a collection of data elements stored in memory. It is the simplest data structure where each data element can be accessed directly by only using its index number. An array is a "special variable", which can hold more than one value.

zero-based indexing

const primitiveDataType = [
    "string", //0
    "int", // 1
    "boolean" //2
];

<br>

## Nested
```
const arrayMain1 = [
  'test1', // [0]
  'test2', // [1]
  'test3', // [2]
  'Elizabeth', // [3]
  [
    // [4]
    'childarray1', // [4][0]
    'childarray2', // [4][1]
    'childarray3', // [4][2]
    {
      // [4][3]
      gcname1: 'grandchild1', // [4][3][0]
      gcname2: 'grandchild2', // [4][3][1]
      gcname3: 'grandchild3', // [4][3][2]
    },
  ],
]
```

## Basic Array Method
### push()
Adds one or more elements to the end of an array and returns the new length of the array

`arrayName.push('Miami');`

<br>

### pop()
Removes the last element from an array and returns that element

`arrayName.pop();`

<br>

### unshift()
adds one or more elements to the beginning of an array and returns the new length of the array

`arrayName.unshift('Cape Town', 'Moscow');`

<br>

### shift()
removes the first element from an array and returns that element.

`arrayName.shift();`



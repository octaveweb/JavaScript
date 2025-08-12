# Datatype
> "use strict"; Defines that JavaScript code should be executed in "strict mode". more [mode details](https://www.w3schools.com/js/js_strict.asp)

### There are Two type of data

1. `Primitive` data type
2. `Reference` or `Non-primitive` data type

## Primitive Data Type

> Primitive data types are basic data types that are built into a programming language. They are the fundamental building blocks of coding.

### There are 7 primitive date types

| Shortcut |   Meaning   |
| :------: | :---------: |
| 🟢 **N** |  `Number`   |
| ⚪ **N** |   `Null`    |
| 🔵 **B** |  `Boolean`  |
| 🟡 **B** |  `BigInt`   |
| 🔴 **S** |  `String`   |
| 🟣 **S** |  `Symbol`   |
| ⚫ **U** | `Undefined` |

### For some Example:

```javascript
const score = 100; // Number
const scoreValue = 100.3; // Decimal Number

const outsideTemp = null; // Null
const forEmptyValue = null; // Null

const isUserLog = true; // Boolean
const isPMisaCook = false; // Boolean

const longInt = 12345678910111213; // BigInt
const numberAfterN = 12345678910111213n; // BigInt


const yourName = "Karan Swarnakar";// String
const youeEmail = "demo@gmail.com";// String

const sym1 = Symbol(); // Symbol - Empty
const sym2 = Symbol("foo"); // Symbol
const sym3 = Symbol("foo"); // Symbol

const userAge; // Undefined
const userPurches; // Undefined
```

## Non-Primitive/Rererence Data Type

> Non-primitive data types, also known as reference types, include objects, arrays, and functions. These types hold references to memory locations rather than the actual data values.

### There are Two type of data

> `Array`, `object`, `function` are the non-primitive data type [mode details](https://262.ecma-international.org/5.1/#sec-11.4.3)

## For some Example:

```javascript
// Array
const heros = ["Batman", "Supperman", "Flash"];
// Object
let myObj = {
  name: "Karan Swarnakar",
  age: 20,
};
// Function
const myFunction = function () {
  console.log("Hello I am a Function");
};
```

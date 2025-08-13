
# Data Conversion
> Data conversion is a part of progaming let think data come from data base and it is in object format so we have to change it to our spacific version of data.

### For Example:

```javascript
const score1 = 33;
const score2 = "33sf";
const score3 = null;
const score4 = undefined;

console.log(typeof score1);
console.log(typeof score2);
console.log(typeof score3);
console.log(typeof score4);
```

### Output:

```javascript
Number
String
Object
undefined
```

| Keyword    | Description |
|------------|------------|
| `Number()` | Converts a value to a number. |
| `String()` | A primitive data type representing text. Strings are immutable, and `String()` is used for converting data into a string. |
| `Boolean()` | Represents a logical value (`true` or `false`). `1` means `true`, `0` means `false`. |

### For Example Number(): 
```javascript
const string_num = "7856321456";
const string_num_cher = "33sf";

const demo1= Number(string_num);
const demo2 = Number(string_num_cher);

console.log(demo1)
console.log(demo2)
```
### Output: 
```javasctipt
7856321456
NaN
```

### Summary: 
```javascript
"43" => 43 
"43abc" => NaN
true => 1 ; false =>0;
```


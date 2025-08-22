# ESM (ECMAScript Modules) vs CJS (CommonJS)

## 1. CommonJS (CJS)

-   Default module system in **Node.js** (before ES Modules support).
    export.
-   Synchronous loading.

### Example (CJS)

**math.js**

``` js
function add(a, b) {
  return a + b;
}

module.exports = { add };
```

**app.js**

``` js
const { add } = require('./math');

console.log(add(2, 3)); // Output: 5
```

------------------------------------------------------------------------

## 2. ECMAScript Modules (ESM)

-   Official JavaScript standard for modules.
-   Uses `import` and `export`.
-   Asynchronous loading, works in browsers and Node.js (with
    `"type": "module"` in `package.json`).

### Example (ESM)

**math.mjs**

``` js
export function add(a, b) {
  return a + b;
}
```

**app.mjs**

``` js
import { add } from './math.mjs';

console.log(add(2, 3)); // Output: 5
```

------------------------------------------------------------------------

## Key Differences

  -----------------------------------------------------------------------
  Feature              CommonJS (CJS)      ECMAScript Modules (ESM)
  -------------------- ------------------- ------------------------------
  Syntax               `require` /         `import` / `export`
                       `module.exports`    

  Loading              Synchronous         Asynchronous

  File Extension       `.js`               `.mjs` (or `.js` with
                                           `"type": "module"`)

  Environment          Node.js (default)   Browser + Node.js

  Exports              Single object       Named & default exports
  -----------------------------------------------------------------------
# Sheryians.com/classroom
## Let's say we have 2 file `script.js` and `script2.js`

## Script.js in `cjs` import and export

### Example:

```javascript
a = 10 
module.exports = a;
```

> i want to get the value of `a` from `script.js` into `script2.js`

 ## Script.js in `cjs` import and export

### Example:

```javascript
require("./script")
console.log(a)
```

### but there is a `issue` we can't send export like this. 

### Main file
```javascript
a = 123
b = 321

// module.exports = a; ❌ Error
// module.exports = b; ❌ Error

module.exports = {a,b} // send an object  
```
> Key points to remember
-  Only one export form one file

- ### Another file
- ```javascript
  const data = require("./script")
  console.log(data)
  ```
  - #### Output
  - ```javascript
    { a: 123, b: 321 }
    ```

> Proparty add in `module.exports.proporty_name = proparty`
### Main file
```javascript
// module.exports = a; ❌ Error
// module.exports = b; ❌ Error
a = 123;
b = 321;
c = 213;

module.exports.a = a 
module.exports.b = b 
module.exports.c = c 
```
- ### Another file
- ```javascript
  const data = require("./script")
  console.log(data)
  ```

- ### Output
- ```javascript
  { a: 123, b: 321, c: 213 }
  ```



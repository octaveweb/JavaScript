# Operation
> Operations like +,-,*,/,**,% for example

| Symbol  | Works                                      |
|---------|--------------------------------------------|
| `+`, `-`, `*`, `/` | Used for basic arithmetic operations |
| `**`     | Used to represent exponentiation (power)  |
| `%`      | Used to get the remainder                |

### Example
```javascript
 console.log(10 + 2 );
 console.log(10 - 2 );
 console.log(10 * 2 );
 console.log(10 ** 2);
 console.log(10 / 2 );
 console.log(10 % 3 );
```
### Output
```javascript
12
8
20
100
5
1
```
## Exercise 1
```javascript
console.log("1" + 2); 
```
So in this case we have **"1" + 2** first of all we have to check both ate number or not but first one is a `String` and second one is a `Number` bacillary it put the value together.    
### Output
```javascript
12
```
## Exercise 2
```javascript
console.log(1 + "2"); 
```
Same like previous one `Number` and another one is a `String`, so both are put together.   
### Output
```javascript
12
```

## Exercise 3
```javascript
console.log("1" + "2"); 
```
In this case first one is `String` and another one is also `String`, so both are put together.   
### Output
```javascript
12
```

## Exercise 4
```javascript
console.log("1" + 2 + 2); 
```
So first one is `String`, `Number`, `Number` no dout both put together.  
### Output
```javascript
122
```

## Exercise 5
```javascript
console.log(1 + 2 + "2"); 
```
But in this case `Number`, `Number`, `String` it is vary intreasting case we know by our previous knowledge that if any String present and add then both values print together but the first two values are number so that add together then the addition value and the string value put togeher,  
### Output
```javascript
32
```



# Memory

> Memory is the brain’s ability to encode, store, and retrieve information, allowing us to learn, adapt, and recall past experiences.

## Types of Memory

Memory is categorized into two types:

## Stack Memory (Primitive)

Used for storing fixed-size data like numbers, booleans, and references.

![Stack Memory](https://imgs.search.brave.com/vJpKex5FwLd9-e7_tnxTJ2csglBZcuSTS8A25NRXS4A/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9yZXMu/Y2xvdWRpbmFyeS5j/b20vZW5kamluL2lt/YWdlL3VwbG9hZC9m/X2F1dG8vcV84MC9h/c3NldHMvaW1hZ2Vz/L2Jsb2cvMjAyMi8w/Ni9zdGFjay1kYXRh/LXN0cnVjdHVyZS5w/bmc)

## Heap Memory (Non-Primitive)

Used for storing dynamic data like objects, arrays, and functions.

![Heap Memory](https://example.com/path/to/heap-memory-image.png)

### Characteristics of Heap Memory:

- **Dynamic Allocation**: Memory is allocated and deallocated at runtime.
- **Flexible Size**: The size of the memory can grow and shrink as needed.
- **Garbage Collection**: JavaScript automatically manages memory allocation and deallocation through garbage collection.

### Example:

```javascript
let person = {
  name: "John",
  age: 30,
};

let numbers = [1, 2, 3, 4, 5];

function greet() {
  console.log("Hello, World!");
}
```
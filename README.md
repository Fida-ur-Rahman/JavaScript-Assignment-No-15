# JavaScript Map & Filter Methods

##  Overview
This repository demonstrates the **JavaScript `map` and `filter` methods** with clear examples. Learn how to transform arrays using `map` and select elements using `filter`. Ideal for practice and portfolio projects.

##  Examples

```javascript
// Map example: double numbers
const numbers = [1, 2, 3, 4];
const doubled = numbers.map(num => num * 2);
console.log(doubled); // [2, 4, 6, 8]

// Filter example: get even numbers
const evenNumbers = numbers.filter(num => num % 2 === 0);
console.log(evenNumbers); // [2, 4]

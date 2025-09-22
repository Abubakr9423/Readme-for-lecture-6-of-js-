# Readme about the 6 lectue about the js

![image](./Logo%20featuring%20the%20J.png)

# Table of content
- 1 Array
- 2 Destructuring
- 3 Spread,rest

# what is Data structure 
Data sructure is the way of organazi information in memory of computer

# array
## = 1 what is array in js An array in JavaScript is a special variable that holds a list of values—like numbers, strings, or objects—in a single, ordered collection accessible by index.

### - array has 3 type of methds 
- 1 methods modify their parent in this method includes:
1.pop(delete the element from the end)
2.push(add the element from the last)
3.shift(delete element from begining)
4.unshift(add element from begining)
5.splice(you can say form where he start how many elements delete and which element add)

- 2 Methods return new parent
without changing the primary parent
1.concat(with help of is we can merge two or more arrays)
2.slice(we say two index and is show from first index to last)
3.join(it make array to single string)
4.toString(it make array to string)
5.toReversed(it make array reverse but we also have reverse and its different from toReversed)

- 3 Methods return new value
1.includes(we say the name of element if we have this variable its show as)
2.indexOf(it show as an index of element)

# js Mechanism 
1.Destructuring assignment
Destructuring is a syntax that lets you unpack values from arrays or properties from objects into distinct variables.
```js
const [a, b] = [1, 2];
console.log(a); // 1
console.log(b); // 2
```
2.Spread syntax(...)
lets you expand elements of an array or object into individual parts.
```js
const nums = [1, 2, 3];
const moreNums = [...nums, 4, 5]; 
// [1, 2, 3, 4, 5]
```
3.Rest parameters
Rest parameters use ... to collect multiple arguments into a single array. They’re used in function definitions to handle variable numbers of arguments.
```js
function sum(...numbers) {
  return numbers.reduce((acc, num) => acc + num, 0);
}

sum(1, 2, 3); // 6
```

![Boolean Tech Academy](https://img.shields.io/badge/Boolean_Tech_Academy-001632?style=for-the-badge)

# 🎓 Exercise 29/50 - JavaScript Array Methods Snacks

## 📌 Project Overview

| Property   | Details               |
| :--------- | :-------------------- |
| Repository | `js-jsnacks-blocco-5` |
| Category   | Boolean Tech Academy  |
| Type       | Exercise              |
| Exercise   | 29/50                 |

## 🎯 Assignment

Use the supplied exercise folder to create a new GitHub repository.

Then solve the following JavaScript snacks using whichever **array methods** you
consider most appropriate.

### Snack 1 - Print Names

Given the following array:

```javascript
const names = ["Edoardo", "Simone", "Francesco"];
```

Print all the names to the console.

**Expected output:**

```javascript
("Edoardo", "Simone", "Francesco");
```

### Snack 2 - Print Names from Objects

Given the following array of objects:

```javascript
const people = [
  { name: "Paolo", age: 35 },
  { name: "Giulia", age: 24 },
  { name: "Marco", age: 67 },
];
```

Print all the names to the console.

**Expected output:**

```javascript
("Paolo", "Giulia", "Marco");
```

### Snack 3 - Increment Numbers

Given the following array:

```javascript
const numbers = [2, 8, 4, 7, 2, 87];
```

Create a new array in which every number is incremented by 1.

**Expected output:**

```javascript
[3, 9, 5, 8, 3, 88];
```

### Snack 4 - Extract Authors

Given the following array of posts:

```javascript
const posts = [
  { author: "Marco", date: "12/3/2021", content: "lorem ipsum..." },
  { author: "Luca", date: "30/6/2021", content: "lorem ipsum..." },
  { author: "Fabrizio", date: "12/9/2020", content: "lorem ipsum..." },
  { author: "Enrico", date: "09/12/2021", content: "lorem ipsum..." },
];
```

Create a new array containing the names of all the authors.

**Expected output:**

```javascript
["Marco", "Luca", "Fabrizio", "Enrico"];
```

### Snack 5 - Filter Even Numbers

Given the following array:

```javascript
const nums = [2, 8, 4, 7, 12, 87];
```

Create a new array containing only the even numbers from the original array.

**Expected output:**

```javascript
[2, 8, 4, 12];
```

### Snack 6 - Filter Zucchini by Length

Given the following array:

```javascript
const zucchine = [
  { type: "Napoletana", weight: 10, length: 4 },
  { type: "Trombetta", weight: 13, length: 16 },
  { type: "Napoletana", weight: 4, length: 23 },
  { type: "Trombetta", weight: 11, length: 6 },
  { type: "Napoletana", weight: 2, length: 17 },
  { type: "Romana", weight: 5, length: 10 },
  { type: "Romana", weight: 7, length: 9 },
  { type: "Trombetta", weight: 3, length: 8 },
  { type: "Calabrese", weight: 6, length: 27 },
  { type: "Calabrese", weight: 14, length: 4 },
];
```

Starting from the provided array, create two separate arrays:

- One containing zucchini that are **at least 15 cm long**.
- Another containing all the remaining zucchini.

### Snack 7 - Find a Student by ID

Given the following array:

```javascript
const students = [
  {
    id: 1,
    name: "Marco Lanci",
    age: 32,
    class: "3C",
  },
  {
    id: 2,
    name: "Mario Banfi",
    age: 34,
    class: "4A",
  },
  {
    id: 3,
    name: "Luigi Banzi",
    age: 33,
    class: "5B",
  },
];
```

Retrieve the student whose ID is `2`.

**Expected output:**

```javascript
{ id: 2, name: 'Mario Banfi', age: 34, class: '4A' }
```

### Snack 8 - Find a Student's Class

Given the following array:

```javascript
const students = [
  {
    id: 1,
    name: "Marco Lanci",
    age: 32,
    class: "3C",
  },
  {
    id: 2,
    name: "Mario Banfi",
    age: 34,
    class: "4A",
  },
  {
    id: 3,
    name: "Luigi Banzi",
    age: 33,
    class: "5B",
  },
];
```

Retrieve the class of the student named **Marco Lanci**.

**Expected output:**

```javascript
"3C";
```

## 🛠️ Technologies

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 💡 What I Learned

- Iterating over arrays using `forEach()`.
- Transforming arrays with `map()`.
- Filtering array elements with `filter()`.
- Finding specific elements with `find()`.
- Extracting object properties from arrays.
- Creating new arrays based on existing data.
- Choosing the most appropriate array method for each task.

## ©️ Credits

Exercise assigned by **Boolean Tech Academy** as part of the Web Development
course - Class 152 - Year 2025-2026

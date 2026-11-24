![Static Badge](https://img.shields.io/badge/Boolean_Tech_Academy-1565C0?style=for-the-badge)

# Exercise 29/50: JavaScript Array Methods Snacks

Practicing JavaScript array methods to iterate, transform, filter, and search arrays of values and objects, using forEach(), map(), filter(), and find().

## Project overview

| Repository | Project | Category | Main Focus | Exercise |
|:--|:--|:--|:--|:--|
| js-jsnacks-blocco-5 | JavaScript Array Methods Snacks | Exercise | JavaScript, array methods, data transformation | 29/50 |

## Assignment

Use the supplied exercise folder to create a new GitHub repository.

Then solve the following JavaScript snacks using the most appropriate array methods.

#### Snack 1: Print names

Given the names array containing a list of names, print all the names to the console.

**Expected output:**

```text
Edoardo
Simone
Francesco
```

#### Snack 2: Print names from objects

Given the people array containing objects with names and ages, print all the names to the console.

**Expected output:**

```text
Paolo
Giulia
Marco
```

#### Snack 3: Increment numbers

Given the numbers array containing numeric values, create a new array in which every number is incremented by 1.

**Expected output:**

```javascript
[3, 9, 5, 8, 3, 88];
```

#### Snack 4: Extract authors

Given the posts array containing objects with authors, dates, and content, create a new array containing the names of all the authors.

**Expected output:**

```javascript
["Marco", "Luca", "Fabrizio", "Enrico"];
```

#### Snack 5: Filter even numbers

Given the nums array containing numeric values, create a new array containing only the even numbers.

**Expected output:**

```javascript
[2, 8, 4, 12];
```

#### Snack 6: Filter zucchini by length

Given the zucchini array containing objects with the type, weight, and length of different zucchini, create two separate arrays.

- One containing zucchini that are at least 15 cm long.
- Another containing all the remaining zucchini.

**Example output:**

```javascript
const zucchineLunghe = [
  { type: "Trombetta", weight: 13, length: 16 },
  { type: "Napoletana", weight: 4, length: 23 },
  { type: "Napoletana", weight: 2, length: 17 },
  { type: "Calabrese", weight: 6, length: 27 }
];

const zucchineCorte = [
  { type: "Napoletana", weight: 10, length: 4 },
  { type: "Trombetta", weight: 11, length: 6 },
  { type: "Romana", weight: 5, length: 10 },
  { type: "Romana", weight: 7, length: 9 },
  { type: "Trombetta", weight: 3, length: 8 },
  { type: "Calabrese", weight: 14, length: 4 }
];
```

#### Snack 7: Find a student by ID

Given the students array containing student records, retrieve the student whose ID is 2.

**Expected output:**

```javascript
{ id: 2, name: 'Mario Banfi', age: 34, class: '4A' }
```

#### Snack 8: Find a student's class

Given the students array containing student records, retrieve the class of the student named Marco Lanci.

**Expected output:**

```javascript
"3C";
```

## Technologies

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## What I learned

- Iterating over arrays using `forEach()`.
- Transforming arrays with `map()`.
- Filtering array elements with `filter()`.
- Finding specific elements with `find()`.
- Extracting object properties from arrays.
- Creating new arrays based on existing data.
- Choosing the most appropriate array method for each task.

## Credits

Exercise assigned by **Boolean Tech Academy** as part of the Web Development course (Class 152, A.Y. 2025-2026).

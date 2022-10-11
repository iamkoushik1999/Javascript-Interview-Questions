<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  <h1>JavaScript Interview Questions</h1>

> Click :star: if you like the project. Pull Request are highly appreciated. Follow me [@iamkoushik](https://twitter.com/iamkoushik1999) for technical updates.

</div>

### Table of Contents

| No. | Questions                                                                                                               |
| --- | ----------------------------------------------------------------------------------------------------------------------- |
| 1.  | [What are the different data types present in javascript ?](#what-are-the-different-data-types-present-in-javascript-?) |
| 2.  | [What is the difference between Undefined & Null ?](#what-is-the-difference-between-Undefined-&-Null-?)                 |
| 3.  | [Difference between “ == “ and “ === “ operators.](#difference-between-“==“-and-“===“-operators.)                       |

1. ### What are the different data types present in javascript ?
   **Primitive types**
   1. String
   2. Number
   3. Big Int
   4. Boolean
   5. Undefined
   6. Null
   7. Symbol

**[⬆ Back to Top](#table-of-contents)**

2. ### What is the difference between Undefined & Null?

| Undefined                                                                      | NULL                                                      |
| ------------------------------------------------------------------------------ | --------------------------------------------------------- |
| The undefined property indicates that a variable has not been declared at all. | The value null represents the absence of any object value |

Undefined Example

```javascript
var demo;
alert(demo); //shows undefined
alert(type of demo); //shows undefined
```

NULL Example

```javascript
var demo = null;
alert(demo); //shows null
alert(typeof demo); //shows object
```

**[⬆ Back to Top](#table-of-contents)**

3. ### Difference between “ == “ and “ === “ operators.

| ==                                                                                                   | ===                                                                                             |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| returns true if operands have the same data type and same value, returns false if the values differ. | returns true only if operands are of the same data type and same value, otherwise returns false |
| Also known as loose equality                                                                         | Also known as strict equality                                                                   |

== Example

```javascript
var x = 2;
x == y; // Returns true since the value of both x and y is the same
```

=== Example

```javascript
var y = "2";
x === y; // Returns false since the typeof x is "number" and typeof y is "string"
```

**[⬆ Back to Top](#table-of-contents)**

4. ### Difference between var and let and const keyword in javascript.

| var                                                                            | let                                                                            | const                                                                                          |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| The scope of a var variable is functional scope.                               | The scope of a let variable is block scope.                                    | The scope of a const variable is block scope.                                                  |
| It can be updated and re-declared into the scope.                              | It can be updated but cannot be re-declared into the scope.                    | It cannot be updated or re-declared into the scope.                                            |
| It can be declared without initialisation.                                     | It can be declared without initialisation.                                     | It cannot be declared without initialisation.                                                  |
| It can be accessed without initialization as its default value is “undefined”. | It can be accessed without initialization as its default value is “undefined”. | It cannot be accessed without initialisation, as it cannot be declared without initialisation. |

**[⬆ Back to Top](#table-of-contents)**

5. ### What is the NaN property in JavaScript?

> NaN property represents the “Not-a-Number” value. It indicates a value that is not a legal number.

```javascript
isNaN("Hello"); // Returns true
isNaN(345); // Returns false
isNaN("1"); // Returns false, since '1' is converted to Number type which results in 0 ( a number)
isNaN(undefined); // Returns true
```

**[⬆ Back to Top](#table-of-contents)**

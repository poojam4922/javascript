Variable and Data types.

Different Data Types in JavaScript:
String: Represents textual data enclosed within single or double quotes.

var greeting = "Hello, World!";
Number: Represents numeric data, including integers and floating-point numbers.

var age = 25;
var pi = 3.14;
Boolean: Represents a logical value indicating true or false.

var isStudent = true;
var hasJob = false;
Undefined: Represents a variable that has been declared but not assigned a value.

var x;
console.log(x); // Output: undefined
Null: Represents the intentional absence of any value.

var y = null;
These data types are fundamental building blocks in JavaScript programming and are used extensively in writing JavaScript code for web development.

Let's expand on the data types in JavaScript to include arrays, objects, and functions:

Array:
Arrays in JavaScript are used to store multiple values in a single variable. They can hold elements of different data types and are indexed starting from zero.

var numbers = [1, 2, 3, 4, 5]; // Array of numbers
var fruits = ['apple', 'banana', 'orange']; // Array of strings
var mixedArray = [1, 'hello', true]; // Array with mixed data types
Arrays offer various methods for manipulating and accessing their elements, such as push, pop, shift, unshift, slice, etc.

Object:
Objects in JavaScript are collections of key-value pairs. They are used to represent complex data structures and are particularly useful for organizing and accessing data in a structured way.

var person = {
    name: 'John',
    age: 30,
    isStudent: false,
    hobbies: ['reading', 'painting', 'coding'],
    address: {
        street: '123 Main St',
        city: 'New York',
        country: 'USA'
    }
};
Objects can contain various data types as property values, including strings, numbers, arrays, other objects, and even functions.

Function:
Functions in JavaScript are blocks of reusable code that can be invoked or called to perform a specific task. They encapsulate a set of statements and can accept parameters and return values.

// Function declaration
function greet(name) {
    return 'Hello, ' + name + '!';
}

// Function expression
var add = function(x, y) {
    return x + y;
};

// Arrow function
var multiply = (a, b) => {
    return a * b;
};

// Function invocation
console.log(greet('Alice')); // Output: Hello, Alice!
console.log(add(5, 3)); // Output: 8
console.log(multiply(2, 4)); // Output: 8
Functions are fundamental to JavaScript programming and are used for implementing logic, modularizing code, and achieving reusability. They can be declared using function declarations, function expressions, or arrow functions.
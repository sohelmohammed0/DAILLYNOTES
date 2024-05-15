# DAILLYNOTES
/*
WHAT IS JAVA SCRIPT: JS is a programming language. We use it to give instructios to the computer. Which is dynamically typed.

input (code) --->  computer ---> out put
instruction 

console.log is used to log (print a message to the console)
console.log("prints the out put")
Example:

console.log("sohel mohammed");
alert("giver popup");

shift+! = boiler plate code

VARIABLES IN JS: Variables are containers which stores the data.

Ex: name = "sohel mohammed";
console.log(name);

NULL:null represents the intentional absence of any object value. It's a special value that indicates the absence of a 
meaningful value.

UNDEFINED: undefined means a variable has been declared but has not been assigned any value, or a property doesn't exist at all.

BOOLEAN:boolean is a primitive data type that represents a logical value. It can have one of two values: true or false. Booleans
are often used in conditional statements and expressions to control the flow of a program.

VARIABLE RULES:
1.Variable names are case sensitive: "a"  and "A" both are different.
2.Only letters, digits, underscore and $ are allowed
3.Onaly a letter, underscore, or $ should be the first character.
4.Reserved words cannot be variable names.

fullName ---> camel case
fullname ---> (not used)
full_name ---> snake case (not used)  
full-name ---> kebab case (not used)
FullName ---> pascal case   (not used)

DEFINING VARIABLES:

Key words should be used before defining variables.

1. LET: let keyword is used to declare a block-scoped variable. Introduced in ECMAScript 6 (ES6), let provides a way to declare
variables that are limited in scope to the block, statement, or expression on which it is used. Variable can't be re-declared but
can be updated. A block scope variable.

2. CONST: const keyword is used to declare variables that cannot be reassigned. Once a const variable is assigned a value, that 
value cannot be changed through reassignment. Variable can't be re-declared or updated. A block scope variable.

3. VAR : var keyword is used to declare variables. It was the primary way of declaring variables before the introduction of let
and const in ECMAScript 6 (ES6). Variables declared with var have function scope or global scope, depending on where they are 
declared. Var can be re-declared and updated.

DATA TYPES IN JAVA SCRIPT:
i) PREMITIVE DATA TYPES:
1.NUMBER: numbers are used to represent numeric data, including integers, floating-point numbers, and special numeric values like
NaN (Not-a-Number) and Infinity. Numbers in JavaScript are a primitive data type, and they can be represented in various formats,
such as decimal (base 10), binary (base 2), octal (base 8), and hexadecimal (base 16).

2.STRING: A string is a primitive data type used to represent text.

3.BOOLEAN: a boolean is a primitive data type that represents a logical value. It can have one of two values: true or false.
Booleans are commonly used in conditional statements and logical operations to control the flow of a program or to represent
binary conditions.

4.UNDEFINED: undefined is a primitive value that represents a variable that has been declared but has not been assigned a value.
It also represents the value returned by functions that do not explicitly return anything. Essentially, undefined indicates the
absence of a meaningful value.

5.NULL: null is a primitive value that represents the intentional absence of any object value. It is often used to indicate that
a variable or property exists but has no meaningful value assigned to it.

6.BIGINT: A BigInt value, also sometimes just called a BigInt, is a bigint primitive, created by appending n to the end of an
integer literal, or by calling the BigInt() function (without the new operator) and giving it an integer value or string value.

7.SYMBOL: A BigInt value, also sometimes just called a BigInt, is a bigint primitive, created by appending n to the end of an
integer literal, or by calling the BigInt() function (without the new operator) and giving it an integer value or string value.

NON PREMETIVE DATA TYPES:
i) OBJECTS: collection of values. Key:value pair are stored.

1.ARRAYS: arrays are used to store multiple values in a single variable. They are a special type of object that provides a way
to organize and access data sequentially. Arrays in JavaScript are dynamic, meaning they can grow or shrink as needed, and they
can hold values of different data types in the same array.

Example:
// Using array literals
let fruits = ["apple", "banana", "orange"];

// Using the Array constructor
let numbers = new Array(1, 2, 3, 4, 5);



2.FUNCTIONS: functions are first-class citizens, meaning they can be treated like any other value. Functions in JavaScript are
objects, and they can be assigned to variables, passed as arguments to other functions, returned from other functions, and stored
in data structures

Example: // Function declaration
function greet(name) {
    return "Hello, " + name + "!";
}

// Function expression
let add = function(x, y) {
    return x + y;
};
let product = {
    name : "pen",
    price :50,
    colour : "black",
    ratings : 4.5,
    "deal of the day" : "istrue",
};
console.log(product.colour)
const profile = {
    userid : "sohel mohammed",
    followers : "25k",
    posts : 0,
    isfollowing : true,
};
console.log(profile)
*/
! [NODEJS.1](https://raw.githubusercontent.com/sohelmohammed0/DAILLYNOTES/7cabd187cdf6bd18e1ae38a0282f95584f8280d6/JAVA%20SCRIPT.png)

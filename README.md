# TypescriptBasics

* [What is Typescript?](#What-is-Typescript)
* [Variables](#TypeScript-Variable)
* Data types
* Inference 
* Assertion
* Loops
* Functions
* Interface
* Class
* Data modifiers
* Name space
* Generic
* Generic interface
* Generic class

#### What is Typescript?
TypeScript is an open-source programming language developed by Microsoft that compiles to JavaScript. Since its release in 2012, the language has remained in active development. typescript is a superset of JavaScript that allows static typing. typescript also has support for interfaces and other things that you don't find in javascript. first thing to note is that typescript is essentially JavaScript you don't have to learn a new programming language. it just adds new features to JavaScript that you can choose to use typescript compiles into JavaScript. so that means that you can run typescript everywhere in the browser or run node js what's also interesting is that your existing JavaScript code is already valid typescript code.

#### TypeScript - Variable
TypeScript follows the same rules as JavaScript for variable declarations. Variables can be declared using: var, let, and const.

var - 
Variables in TypeScript can be declared using var keyword, same as in JavaScript. The scoping rules remains the same as in JavaScript.

let - 
To solve problems with var declarations, ES6 introduced two new types of variable declarations in JavaScript, using the keywords let and const. TypeScript, being a superset of JavaScript, also supports these new types of variable declarations.

#### TypeScript Data Type - Number
Just like JavaScript, TypeScript supports number data type. All numbers are stored as floating point numbers. These numbers can be Decimal (base 10), Hexadecimal (base 16) or Octal (base 8).

#### Type Inference in TypeScript
TypeScript is a typed language. However, it is not mandatory to specify the type of a variable. TypeScript infers types of variables when there is no explicit information available in the form of type annotations.

Types are inferred by TypeScript compiler when:

* Variables are initialized

* Default values are set for parameters

* Function return types are determined

#### Type Assertion in TypeScript
Here, you will learn about how TypeScript infers and checks the type of a variable using some internal logic mechanism called Type Assertion.

Type assertion allows you to set the type of a value and tell the compiler not to infer it. This is when you, as a programmer, might have a better understanding of the type of a variable than what TypeScript can infer on its own. Such a situation can occur when you might be porting over code from JavaScript and you may know a more accurate type of the variable than what is currently assigned. It is similar to type casting in other languages like C# and Java. However, unlike C# and Java, there is no runtime effect of type assertion in TypeScript. It is merely a way to let the TypeScript compiler know the type of a variable.

(Resources : https://www.tutorialsteacher.com/)


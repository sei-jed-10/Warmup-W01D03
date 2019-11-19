[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)

# Warmup

#### Learning Objectives

- Practice using conditionals.

#### Prerequisites

- Introductory lesson to JavaScript

---



## Directions
Write  `if`, or `if, else` statements to complete the following questions. Some of the problems may require you to use a  conditional. Refer back to your class notes from today if you need help.

## Conceptual Questions

Rate your understanding of the following questions on a scale of 1 - 5. If your understanding is less than or equal to 3, research the answer or ask for help:

1. How do we assign a value to a variable? // by "=" sign 
  - Which line(s) is/are valid?

    ```js
    let a = 0;    // valid
    const b = 1; // valid
    9 = a;      // not valid
    b = b + 5; //valid
    ```

2. How do we change the value of a variable? // we use the declared variable and assign new value to it for "ex. let a = 0; a = 9;"
3. How do we assign an existing variable to a new variable? // for ex. const b = 1; let a = b;

## Let's get Mathy!

```js
const a = 42.78 
const b = 1.1
const c = -2
const d = .5
const e = 16
```

- Round `a` down 
//solution 
const a = 42.78;
let m = Math.floor(a);
console.log(m);

- Round `b` up
//solution 
const b = 1.1;
let m = Math.ceil(b);
console.log(m);

- Find the absolute value of `b - a`
//solution 
const a = 42.78;
const b = 1.1;
let m = Math.abs(a + b);
console.log(m);

- Find the square root of `e`
//solution 
const e = 16
let m = Math.sqrt(e);
console.log(m);

- Raise `e` to the power of `d`
//solution 
const e = 16;
const d = .5;
let m = Math.pow(e, d);
console.log(m);

- Make a digital die 0 generate a random number between 1 - 6 
//solution
let digital = Math.floor(Math.random() * 6) + 1;
console.log(digital);

## Strings Activity 1

### Strings - Switcharoo
1. Create a variable called `firstVariable`.
1. assign it the value of a string: `"Hello World"`
1. On the next line, change the value of this variable to a number.
1. store the value of `firstVariable` into a new variable called `secondVariable`
1. On the next line, change the value of `secondVariable` to a string.
1. What is the value of `firstVariable`? // firstVariable = 5
//solution
let firstVariable = "Hello World";
firstVariable = 5;
let secondVariable = firstVariable;
secondVariable = "Hello";

console.log(firstVariable);  

### Strings - Combine it
1. Create a variable called `yourName` and set it equal to your name as a string.
  - Write an expression that takes the string "Hello, my name is " and the variable `yourName` so that it prints a new string with them concatenated

>ex: `Hello, my name is Jean Valjean`
//solution
let yourName = "Sara";
console.log("Hello, my name is " + yourName);

## Booleans Activity
- Using the provided variable definitions, replace the blanks with a mathematical or boolean operator **that evaluates the expression to true**.

[MDN Comparison Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators)

```
  const a = 6;
  const b = 100;
  const c = -5;
  const d = 3000;
  const e = 'Jelly Bean';
```
//solution
1.  a !== b;
1.  c !== d;
1.  'Peanut' === 'Peanut';
1.  a !== b && b !== c;
1.  a === a && a !== d;
1.  e === 'Jelly Bean';
1.  48 == '48';
1. 'e' !== 'Eh'

## The Age Calculator

Forgot how old someone is? Calculate it!

- Store the current year in a variable.
- Store their birth year in a variable.
- Calculate their 2 possible ages based on the stored values.
- Output them to the screen like so: "They are either NN or NN", substituting the values.

// The Age Calculator
// Forgot how old someone is? Calculate it!

// Store the current year in a variable.
// Store their birth year in a variable.
// Calculate their 2 possible ages based on the stored values.
// Output them to the screen like so: "They are either NN or NN", substituting the values.

//solution
let currentYear = 2019;
let BirthYear = 1995;

let age1 = currentYear - BirthYear;
let age2 = age1 - 1; 
console.log("They are either " + age1 " or " "age2");

## The World Translator
// Write an if statement that writes Hello World in different languages (i.e. if the language is English, print `"Hello World"`, if the language is Arabic write something `"مرحبا بالعالم"`, if the language is French write something romantic)
//solution
let english = "Hello World";
let arabic = "مرحبا بالعالم";
let france = "l'amour";

let language;

if(language == english){
  console.log(english);
}else if(language == arabic){
  console.log(arabic);
}else if(language == france){
  console.log(france);
}

console.log(language = english);
console.log(language = arabic);
console.log(language = france);

 ## Driving Age
// - Store the user age
// - If age is less than 18, print "Sorry, you can't drive yet"
// - If the age is equal to or over 18, print "Drive away!"
// - Bonus: If the user can't drive yet, tell them how many years they will have to wait. E.g. "Sorry, you have 4 years to wait until you can drive"
//solution
let userAge = 15;

if(userAge <= 18 ){
  console.log("Sorry, you can't drive yet");
}else if(userAge >= 18){
  console.log("Drive away!");
}

## The Temperature Converter
// It's hot out! Let's make a converter based on the steps here.
// Store a celsius temperature into a variable.
// Convert it to fahrenheit and output "NN°C is NN°F".
// Now store a fahrenheit temperature into a variable.
// Convert it to celsius and output "NN°F is NN°C."

//solution
function celsius(celsiusTemperature){
let calculateF = (celsiusTemperature * 1.8) + 32;
console.log(calculateF + "°F is " + celsiusTemperature + "°C ");
}

function fahrenheit(fahrenheitTemperature){
let calculateC = (fahrenheitTemperature - 32) / 1.8;
console.log(calculateC + "°C is " + fahrenheitTemperature + " °F");
}

fahrenheit(-2);
celsius(-2);

## The Fortune Teller
// Why pay a fortune teller when you can just program your fortune yourself?

// Store the following into variables: number of children, partner's name, geographic location, job title. Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."

//solution
let numberOfChildren = 3;
let partnerName = "name";
let geographicLocation = "Australia";
let jobTitle = "Full Stack Developer";

console.log("You will be a " + jobTitle + " in " + geographicLocation + " ,and married to "+  partnerName + " with " + numberOfChildren + " kids.");

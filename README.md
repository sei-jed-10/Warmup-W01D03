[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)

# Warmup

#### Learning Objectives

- Practice using conditionals and / or loops to solve problems

#### Prerequisites

- Introductory lesson to JavaScript

---

## Getting Started

1. Navigate into the `student_examples` folder for today.

2. Create a file called `morning_lab_solutions.js` .



## Directions
Write loops, `if`, or `if, else` statements to complete the following questions. Some of the problems may require you to use a loop inside the conditional. Refer back to your class notes from today if you need help.

## Conceptual Questions

Rate your understanding of the following questions on a scale of 1 - 5. If your understanding is less than or equal to 3, research the answer or ask for help:

1. How do we assign a value to a variable?
  - Which line(s) is/are valid?

    ```js
    let a = 0; valid
    const b = 1; valid
    9 = a; invalid
    b = b + 5; valid
    ```

2. How do we change the value of a variable?
assign the new value to the variable's name by using the assignment "=" operator like this:
number=6;
3. How do we assign an existing variable to a new variable?
var newVariable=existingVariable;

## Let's get Mathy!

```js
const a = 42.78
const b = 1.1
const c = -2
const d = .5
const e = 16
```

- Round `a` down
- Round `b` up
- Find the absolute value of `b - a`
- Find the square root of `e`
- Raise `e` to the power of `d`
- Make a digital die 0 generate a random number between 1 - 6 

//Round a down
const a = Math.floor(42.78);

//Round b up
const b = Math.ceil(1.1);

//Find the absolute value of b - a
console.log(Math.abs(b-a));

const c = -2

//Find the square root of e
const e = 16
console.log(Math.sqrt(e));

//Raise e to the power of d
const d = .5
console.log(Math.pow(e,d));

//Make a digital die 0 generate a random number between 1 - 6
console.log(Math.floor(Math.random()*6)+1);

## Strings Activity 1

### Strings - Switcharoo
1. Create a variable called `firstVariable`.
1. assign it the value of a string: `"Hello World"`
1. On the next line, change the value of this variable to a number.
1. store the value of `firstVariable` into a new variable called `secondVariable`
1. On the next line, change the value of `secondVariable` to a string.
1. What is the value of `firstVariable`? It has the last value assigned to it (a number).

var firstVariable="Hello World";
firstVariable=7;
var secondVariable=firstVariable;
secondVariable="Hello"
console.log(firstVariable);

### Strings - Combine it
1. Create a variable called `yourName` and set it equal to your name as a string.
  - Write an expression that takes the string "Hello, my name is " and the variable `yourName` so that it prints a new string with them concatenated

>ex: `Hello, my name is Jean Valjean`

var Sarah="Sarah";
console.log("Hello, my name is "+Sarah);

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

1.  a <b;
1.  c < d;
1.  'Peanut' == 'Peanut';
1.  (a < b) > c;
1.  (a == a) < d;
1.  e =='Jelly Bean';
1.  48 == '48';
1. 'e' !=='Eh'

## The Age Calculator

Forgot how old someone is? Calculate it!

- Store the current year in a variable.
- Store their birth year in a variable.
- Calculate their 2 possible ages based on the stored values.
- Output them to the screen like so: "They are either NN or NN", substituting the values.

// The Age Calculator
// Forgot how old someone is? Calculate it!

// Store the current year in a variable.
var currentYear="2019"
// Store their birth year in a variable.
var birthYear="1995"
// Calculate their 2 possible ages based on the stored values
var ageGuess1=currentYear-birthYear;
var ageGuess2=ageGuess1-1;
// Output them to the screen like so: "They are either NN or NN", substituting the values.
console.log("They are either "+ageGuess1+" or "+ageGuess2);

## The World Translator
// Write an if statement that writes Hello World in different languages (i.e. if the language is English, print `"Hello World"`, if the language is Arabic write something `"مرحبا بالعالم"`, if the language is French write something romantic)
var language="English";

if (language=="English"){
  console.log("Hello world");
}
else if (language=="Arabic"){
  console.log("مرحبًا بالعالم");
}
else if (language=="French"){
  console.log("Bonjour");
}

 ## Driving Age
// - Store the user age
// - If age is less than 18, print "Sorry, you can't drive yet"
// - If the age is equal to or over 18, print "Drive away!"
// - Bonus: If the user can't drive yet, tell them how many years they will have to wait. E.g. "Sorry, you have 4 years to wait until you can drive"

 ## Solution
var age=17;
if (age<18){
  var yearsLeft=18-age;
  if (yearsLeft==1){
  console.log("Sorry, you can't drive yet\n You need to wait one more year to drive.");
  }
  else{
      console.log("Sorry, you can't drive yet\n You need to wait "+yearsLeft+" more years to drive.");
  }
}
else{
  consle.log("Drive Away!");
}

## The Temperature Converter
// It's hot out! Let's make a converter based on the steps here.
// Store a celsius temperature into a variable.
// Convert it to fahrenheit and output "NN°C is NN°F".
// Now store a fahrenheit temperature into a variable.
// Convert it to celsius and output "NN°F is NN°C."
var cTempreture=30;
var fTempreture=cTempreture*(9/5)+32;
console.log(fTempreture+"°F is "+cTempreture+"°C." )

## The Fortune Teller
// Why pay a fortune teller when you can just program your fortune yourself?

// Store the following into variables: number of children, partner's name, geographic location, job title. Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."
var numberOfChildren=4;
var partnerName="an Unlucky Human";
var geographicLocation="the US";
var jobTitle="CEO of a Tech Company";
console.log("You will be a "+ jobTitle+" in "+ geographicLocation+", and married to "+partnerName+" with "+ numberOfChildren+" kids.");

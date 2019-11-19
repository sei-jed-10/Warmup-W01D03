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

1. How do we assign a value to a variable?
  - Which line(s) is/are valid?

    ```js
    let a = 0; TRUE
    const b = 1; TRUE
    9 = a; FALSE
    b = b + 5; FALSE
    ```

2. How do we change the value of a variable?
BY DECLAIRE IT AGAIN WITH THE NEW VALUE
3. How do we assign an existing variable to a new variable?
let a = "faisal"
a = "iFaisalo"
## Let's get Mathy!

```js
const a = 42.78
const b = 1.1
const c = -2
const d = .5
const e = 16
```

- Round `a` down
Math.floor(a)
- Round `b` up
Math.round(b)
- Find the absolute value of `b - a`
Math.floor(b-a)
- Find the square root of `e`
Math.sqrt(e)
- Raise `e` to the power of `d`
Math.pow(e, d)
- Make a digital die 0 generate a random number between 1 - 6 
console.log (Math.floor((Math.random())*6)+1)

## Strings Activity 1

### Strings - Switcharoo
1. Create a variable called `firstVariable`.
1. assign it the value of a string: `"Hello World"`
1. On the next line, change the value of this variable to a number.
1. store the value of `firstVariable` into a new variable called `secondVariable`
1. On the next line, change the value of `secondVariable` to a string.
1. What is the value of `firstVariable`?
let firstVariable = "Hello World"
firstVariable = 123
secondVariable = firstVariable

### Strings - Combine it
1. Create a variable called `yourName` and set it equal to your name as a string.
  - Write an expression that takes the string "Hello, my name is " and the variable `yourName` so that it prints a new string with them concatenated

>ex: `Hello, my name is Jean Valjean`

let yourName = "iFaisalo"

console.log ("Hello, my name is " + yourName)

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

1.  a < b;
1.  c < d;
1.  'Peanut' == 'Peanut';
1.  a < b > c;
1.  a == a < d;
1.  e == 'Jelly Bean';
1.  48 !== '48';
1. 'e' !== 'Eh'

## The Age Calculator

Forgot how old someone is? Calculate it!

- Store the current year in a variable.
- Store their birth year in a variable.
- Calculate their 2 possible ages based on the stored values.
- Output them to the screen like so: "They are either NN or NN", substituting the values.

let currentYear = 2019
let yourBirthYear = 1988
let age = currentYear - yourBirthYear

console.log ("They are either " + age + " or " + (age - 1))
// The Age Calculator
// Forgot how old someone is? Calculate it!

// Store the current year in a variable.
// Store their birth year in a variable.
// Calculate their 2 possible ages based on the stored values.
// Output them to the screen like so: "They are either NN or NN", substituting the values.

## The World Translator
// Write an if statement that writes Hello World in different languages (i.e. if the language is English, print `"Hello World"`, if the language is Arabic write something `"مرحبا بالعالم"`, if the language is French write something romantic)

let languageEnglish = "english"
let languageArabic = "arabic"
let languageFrinch = "frinch"

let tran = ""

if (tran == languageEnglish) consol.log ("Hello World")
else if (tran == languageArabic) console.log ("مرحبًا بالعالم")
else if (tran == languageFrinch) console.log ("somthing romantic")
else console.log ("try again")

 ## Driving Age
// - Store the user age
// - If age is less than 18, print "Sorry, you can't drive yet"
// - If the age is equal to or over 18, print "Drive away!"
// - Bonus: If the user can't drive yet, tell them how many years they will have to wait. E.g. "Sorry, you have 4 years to wait until you can drive"

let userAge = ""

if (userAge < 18 ) {
  console.log ("Sorry, you can't drive yet")
  console.log ("but you have " + (18 - userAge) + " years to wait until you can drive")
} else console.log ("Drive away!")




## The Temperature Converter
// It's hot out! Let's make a converter based on the steps here.
// Store a celsius temperature into a variable.
// Convert it to fahrenheit and output "NN°C is NN°F".
// Now store a fahrenheit temperature into a variable.
// Convert it to celsius and output "NN°F is NN°C."

let celTemp = 26
let fahTemp = celTemp * (9/5) + 32

console.log (Math.floor(fahTemp) + "°F is " + celTemp +"°C.")
## The Fortune Teller
// Why pay a fortune teller when you can just program your fortune yourself?

// Store the following into variables: number of children, partner's name, geographic location, job title. Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."

let numOfChild = ""
let partnerName = ""
let geoLocation = ""
let jobTitle = ""

console.log ("You'll ba a " + jonTitle + " in " + geoLocation + ", and married to " + partnerName + " with " + numOfChild + " kids.")
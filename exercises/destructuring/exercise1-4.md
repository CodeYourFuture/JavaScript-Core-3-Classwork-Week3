# Exercises

## Exercise 1

We have the names of the Simpsons family stored in an array called `familyMembers`. Create variables to store the names of the family members so that the `console.log` will print out the following message: `In the Simpsons family, Homer and Marge are the parents. Bart is the son, Lisa is the daughter, and Maggie is the baby.`

```js
let familyMembers = ["Homer", "Marge", "Bart", "Lisa", "Maggie"];

// Create variables to store the values here

console.log(
  `In the Simpsons family, ${dad} and ${mum} are the parents. ${son} is the son, ${daughter} is the daughter, and ${baby} is the baby.`
);

```

**Question**: How many lines of code did you add?

## Exercise 2

Rewrite the code below to use array destructuring instead of assigning each value to a variable.

```js
let sentence = ["Hello", "Code", "Your", "Future"];

let firstWord = item[0];
let secondWord = item[1];
let thirdWord = item[2];
let fourthWord = item[3];

console.log(
  `FirstWord: ${firstWord}, SecondWord: ${secondWord}, ThirdWord: ${thirdWord}, FourthWord: ${fourthWord},`
);
```

## Exercise 3

We have a function called `sumAndMultiply`. It will take two numbers and then return an array where the first number is the sum of the two numbers, and the second number is the multiplication of the two numbers.

```js
function sumAndMultiply(a, b) {
  return [a + b, a * b];
}

// Assign variables using array destructuring on this line

console.log(
  `The sum of the two numbers is ${sum}, the multiplication of the two numbers is ${multiply}`
);
```

Which of the following lines of code can be used above?

- A) let sum, multiply = sumAndMultiply(2, 3);
- B) let [sumAndMultiply] = sumAndMultiply(2, 3);
- C) let [sum, multiply] = sumAndMultiply(a, b);
- D) let [sum, multiply] = sumAndMultiply(2, 3);

## Exercise 4

When you do array destructuring, the array can be of any data type. Try destructuring with the next array, which contains objects.

```js
let citiesByPopulation = [
  { name: "London", population: 8000000 },
  { name: "Birmingham", population: 1000000 },
  { name: "Glasgow", population: 600000 },
  { name: "Manchester", population: 500000 },
];

// Assign variables using array destructuring on this line

console.log(`${london.name} population is ${london.population}`);
console.log(`${birmingham.name} population is ${birmingam.population}`);
console.log(`${glasgow.name} population is ${glasgow.population}`);
console.log(`${manchester.name} population is ${manchester.population}`);
```

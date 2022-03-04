# Exercises

Rewrite the code below to use object destructuring instead of assigning each value to a variable.

```js
let family = {
  mum: "Marge",
  dad: "Homer",
  children: {
    son: "Bart",
    daughter: "Lisa",
    baby: "Maggie",
  },
};

console.log(`
  In the Simpsons family, ${dad} and ${mum} are the parents. `);

console.log(`
  In the Simpsons family there are 3 children, ${son} is the son, ${daughter} is the daughter, and ${baby} is the baby.`);
```

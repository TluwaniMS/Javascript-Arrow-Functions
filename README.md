# Javascript-Arrow-Functions

`Arrow functions` are/offer a shorter way of writing Javascript functions.

```
function greetTheWorld() {
  console.log(`Hello World!!`);
}

/// Arrow function equivalent:
const greetTheWorld = () => console.log(`Hello World!!`);
```


```
function sayMyName(name) {
  console.log(`Hey ${name}!`);
}

/// Arrow function equivalent:
const sayMyName = (name) => console.log(`Hey ${name}!`);
```

```
function generateEmail(name) {
  return `${name}@mock.com`;
}

/// Arrow function equivalent:
const generateEmail = (name) => `${name}@mock.com`;
```

```
function generateSumAndlogIt(a, b) {
  const sum = a + b;

  console.log(`The sum of ${a} and ${b} is ${sum}`);
}

/// Arrow function equivalent:
const generateSumAndlogIt = (a, b) => {
  const sum = a + b;

  console.log(`The sum of ${a} and ${b} is ${sum}`);
};
```

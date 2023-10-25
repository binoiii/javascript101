# Functions and Scope

## Function Declaration vs Expression

### Function Declaration

Create a function iwth a name.

Example:

```javascript
greet() // Output: Hello!

function greet() {
  console.log('Hello!')
}

const add = function (a, b) {
  return a + b
}

const add = (a, b) => a + b
```

#### Usage of Function Declaration

- Abstraction: Allow you to use function declarations before they are defined.
- Global Scope: Function is available throughout the code.
- Performance: Because variable declarations are moved to the top of their scope during compilation this may reduce the time the JavaScript engine needs to parse the code.
- [Read more](https://dev.to/jwwnz/javascript-hoisting-what-it-is-and-why-it-was-implemented-51ep).

### Function Expression

Example:

```javascript
const doStuff = function () {}
```

#### Usage of Function Expression

Avoids polluting global scope: Limit where the function is available.

## Scope

It is the visibility and accessibility of the variables within different parts of a program.

### Global

Variables declared outside of any function which accessible throughout the code.

#### Usage of Globally Scope Variables

Maximize accessible (But it has its own trade offs)

### Local

Variables declared inside the function which are accessible only within the function

#### Usage of Locally Scope Variables

For encapsulation

## Use of Arrow Function

Arrow functions have a more concise syntax compared to traditional functions (Syntactic sugar)

- Better readability
- Has an implicit return

Arrow functions do not have their own this. They inherit the this value from the surrounding code.

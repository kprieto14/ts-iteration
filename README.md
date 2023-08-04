# TypeScript Iteration

## Instructions

1. Fork [this repository](https://github.com/suncoast-devs/js-iteration) to your own account.
2. Change into your projects directory:
3. Clone your repository: `hub clone js-iteration`
4. Change into your project's directory: `cd js-iteration`
5. Install the dependencies: `npm install`
6. Open in your editor: `code .`
7. Start the test runner: `npm start`
8. Open `src/functions.ts` and work on functions until tests pass.


function isMoreThan50(value) {
  return value > 50
}

const numbers = [51, 100, 99]
console.log(numbers.every(isMoreThan50)) // logs true

const otherNumbers = [51, 100, 49]
console.log(otherNumbers.every(isMoreThan50)) // logs false


const numbers = [42, 100, 19, 33, 66, 50]
const firstNumberMoreThan50 = numbers.find(number => number > 50)
console.log(firstNumberMoreThan50) // Logs 100



function isMoreThan50(value) {
  return value > 50
}

const numbers = [1, 2, 51]
console.log(numbers.some(isMoreThan50)) // logs true

const otherNumbers = [1, 2, 3]
console.log(otherNumbers.some(isMoreThan50)) // logs false
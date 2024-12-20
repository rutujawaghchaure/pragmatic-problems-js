# Pragmatic JS

This repository contains a collection of Codeforces problems with automated tests to help you verify your solutions.

## Setup Instructions

1. Make sure you have Node.js installed on your computer.

2. Clone this repository:
```bash
git clone <repository-url>
cd <repository-name>
```

3. Install the dependencies:
```bash
npm install
```

## Writing Your Solutions

1. All your solution files should be placed in the `solutions/` directory.
2. Name your solution files exactly as mentioned (e.g., q1.js, q2.js, etc.)
3. Each solution file should export its function using `export default`
4. Make sure to use the exact function name as mentioned in the corresponding test file

Example:
If test file `tests/q1.test.js` has:
```javascript
import myFunction from '../solutions/q1.js'
```
Then your `solutions/q1.js` should look like:
```javascript
const myFunction = (param1, param2) => {
    // Your solution here
}

export default myFunction
```

## Running Tests

To test your solutions, use one of these commands:

- Run tests once:
```bash
npm test
```

- Run tests in watch mode (tests re-run when you save changes):
```bash
npm run test:watch
```

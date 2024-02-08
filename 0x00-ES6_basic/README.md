# 0x00. ES6 Basics - JavaScript ES6

## Project Overview

This project, spanning from Jan 2, 2024, 6:00 AM, to Jan 4, 2024, 6:00 AM, focuses on essential ES6 concepts in JavaScript, such as software linting and general JavaScript programming. The primary learning objectives include understanding ES6 features, distinguishing between constants and variables, grasping block-scoped variables, mastering arrow functions and default parameters, and exploring rest and spread function parameters. The project is structured with specific tasks, each contributing to a comprehensive understanding of ECMAScript 2015 (ES6) and enhancing JavaScript programming skills.

## Concepts Covered

- Software Linter
- JavaScript programming
- ECMAScript 6 (ES6)
- Statements and declarations
- Arrow functions
- Default parameters
- Rest parameter
- ES6 Iterables & Iterators

## Learning Objectives

Upon completion of this project, participants are expected to explain ES6, identify its new features, distinguish between constants and variables, understand block-scoped variables, utilize arrow functions and default parameters, work with rest and spread function parameters, employ string templating in ES6, create objects and their properties in ES6, and comprehend iterators and for-of loops.

## Requirements

- All files executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- Files should end with a new line
- Mandatory README.md file at the project root
- Code files must use the `.js` extension
- Code tested using the Jest Testing Framework
- Code analyzed using ESLint with provided rules
- All functions must be exported

## Setup

1. Install NodeJS 12.11.x in your home directory:

   ```bash
   curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
   sudo bash nodesource_setup.sh
   sudo apt install nodejs -y
   ```

2. Verify the installation:

   ```bash
   nodejs -v
   npm -v
   ```

3. Install Jest, Babel, and ESLint:

   In your project directory, run:

   ```bash
   npm install
   ```

4. Configuration files:

   Add the following files to your project directory:

   - `package.json`
   - `babel.config.js`
   - `.eslintrc.js`

5. Run:

   Don't forget to run `npm install` from the terminal of your project folder to install all necessary project dependencies.

## Tasks (Example)

### 0. Const or let?

Modify the `taskFirst` function to instantiate variables using `const` and the `taskNext` function to use `let`:

```javascript
export function taskFirst() {
  const task = 'I prefer const when I can.';
  return task;
}

export function getLast() {
  return ' is okay';
}

export function taskNext() {
  let combination = 'But sometimes let';
  combination += getLast();
  return combination;
}
```

Execution example:

```bash
$ cat 0-main.js
import { taskFirst, taskNext } from './0-constants.js';

console.log(`${taskFirst()} ${taskNext()}`);
```

Output:

```
I prefer const when I can. But sometimes let is okay
```
Lets Go!!!

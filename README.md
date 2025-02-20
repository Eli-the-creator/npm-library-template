# This is my template for creating an NPM library or package

## Feel free to use 🚀

This repository serves as a starter template for developing and publishing an NPM library or package. It includes essential configurations, scripts, and best practices to streamline the development process.

---

## Features
- Pre-configured **ESLint** and **Prettier** for code consistency
- **TypeScript** support (optional, can be removed)
- Ready-to-use **Jest** setup for testing
- GitHub Actions for **CI/CD**
- Automated **NPM publishing** workflow
- Example **usage and setup** included
- Pre-configured **package.json** with necessary fields

---

## Installation
Clone this repository and run:
```sh
git clone https://github.com/Eli-the-creator/npm-library-template.git
```

---

## Usage
Modify the `src/index.js` or `src/index.ts` file with your custom package logic. Export your modules as needed.

Example:
```js
// src/index.js
export function helloWorld() {
  return "Hello, NPM!";
}
```
Then, import and use it in another project:
```js
import { helloWorld } from 'your-package-name';
console.log(helloWorld()); // "Hello, NPM!"
```

---

## Scripts
Run the following commands:
- `npm run build` – Build the package
- `npm test` – Run tests with Jest
- `npm publish` – Publish to NPM (ensure you're logged in)
- `npm version patch` – Update version (use `minor` or `major` as needed)

---

## Publishing to NPM
1. Ensure you have an NPM account (`npm login`).
2. Run `npm publish` to deploy your package.

For scoped packages (`@username/package-name`), use:
```sh
npm publish --access public
```

---



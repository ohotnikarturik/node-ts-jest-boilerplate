# Node.js, TypeScript boilerplate

```
npm init
```

> The `npm init` command in the JSON language creates a package. json file for your project's. A package. json file is a file that contains information about the project's packages and dependencies

<br />

```
npm install typescript --save-dev
```

> TypeScript is a language for application-scale JavaScript development. It's a typed superset of JavaScript that compiles to plain JavaScript.

<br />

```
npm install ts-node --save-dev
```

> `ts-node` is an npm package which allows the user to run typescript files directly, without the need for precompilation using tsc

<br />

```
npm install @types/node --save-dev
```

> This package contains type definitions for Node.js

<br />

```
npx tsc --init
```

> Creates a new tsconfig.json file
> The tsconfig.json file allows you to specify the root level files and the compiler options that requires to compile a TypeScript project.

<br />

```
npm install eslint --save-dev
```

> ESLint is a static code analysis tool for identifying problematic patterns found in JavaScript code.
> Linters check your code for syntax errors and highlight errors to make sure you can quickly find and fix them. ESLint is a linter that you can integrate into your Visual Studio Code setup in order to ensure code integrity. ESLint can both format your code and analyze it to make suggestions for improvement.

<br />

```
npm init @eslint/config
```

> `eslint --init` is intended for setting up and configuring ESLint on a per-project basis and will perform a local installation of ESLint and its plugins in the directory in which it is run

<br />

```
npm install prettier --save-dev
```

> Prettier helps you write more consistent code. You see patterns better when your code is formatted correctly. When your code doesn't format on save, you start immediately recognizing when your code has errors. Please consider using Prettier, it'll make your dev process much more enjoyable!

<br />

```
npm install eslint-plugin-prettier eslint-config-prettier --save-dev
```

> `eslint-plugin-prettier` Runs Prettier as an ESLint rule and reports differences as individual ESLint issues.

> `eslint-config-prettier` Turns off all rules that are unnecessary or might conflict with Prettier.
> This lets you use your favorite shareable config without letting its stylistic choices get in the way when using Prettier.

<br />

```
npm install eslint-import-resolver-typescript tsconfig-paths --save-dev
```

> `eslint-import-resolver-typescript` This plugin adds TypeScript support to eslint-plugin-import.

> `tsconfig-paths` Use this to load modules whose location is specified in the paths section of tsconfig.json

<br />

```
npm install nodemon --save-dev
```

> nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected

<br />

```
npm install dotenv-safe @types/dotenv-safe --save-dev
```

> Identical to dotenv, but ensures that all necessary environment variables are defined after reading from .env. These needed variables are read from .env.example, which should be commited along with your project.

<br />

```
npm install jest ts-jest @types/jest --save-dev
```

> Jest is a JavaScript test runner, that is, a JavaScript library for creating, running, and structuring tests. Jest ships as an NPM package, you can install it in any JavaScript project.

<br />

```
npx ts-jest config:init
```

> config:init creates default jest.config.js file

<br />

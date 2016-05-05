# Typescript boilerplate
A boilerplate project for typescript and jasmine. Uses systemJs and the tsconfig contains the information for transpiling ts to js.

## Commands one shall use

* npm start - runs the compiler and a server at the same time, both in "watch mode"
* npm run tsc - runs the TypeScript compiler once
* npm run tsc:w - runs the TypeScript compiler in watch mode; the process keeps running, awaiting changes to TypeScript files and re-compiling when it sees them
* npm run lite - runs the lite-server, a light-weight, static file server
* npm run typings - runs the typings tool
* npm run postinstall - called by npm automatically after it successfully completes package installation. This script installs the TypeScript definition files defined in typings.json
* npm test - runs the test cases
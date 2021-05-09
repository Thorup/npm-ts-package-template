[![TypeScript](https://img.shields.io/badge/typescript-4.2.4-blue)](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-4-2.html)
[![npm](https://img.shields.io/badge/npm-7.5.2-blue)](https://www.npmjs.com/package/npm/v/7.5.4)
[![node](https://img.shields.io/badge/node-15.4.0-blue)](https://nodejs.org/docs/latest-v15.x/api/)
# Template base for developing npm packages using typescript.

## Setup
- Ensure that you are using compatible versions of npm, node and typescript.
- Clone the project.
- Run `$ npm i`
- The project uses eslint and prettier. For a good experience you can install extensons for you editor which automates some of the commands, as calling prettier on save ect.
- Run `$ npm build`. To generate distribution files.
- To test your module use the `npm link`. See the [docs](https://docs.npmjs.com/cli/v7/commands/npm-link).

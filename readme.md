# Foot - my project needs a foot to stand on

A boilerplate project and structure for a Node.js with TypesScript and all the trimming such as EsLint, Jest, Cypress, etc.

![Image of foot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPwxY9RAzNdV7Bt6DQk8BBuLgW-iyQ-gmr4g&usqp=CAU)

I was tired of doing all of the base setup and config work to establish a node project

# start your own project

## Getting Started

Get a clone of this project named correctly using Degit

    npx degit jordan112/foot#main my-new-node-app

Install all the dependencies

    yarn

Build and start the project

    yarn start

Or if you want one big super command line:

    npx degit jordan112/foot#main my-new-node-app && cd $_ && yarn && yarn start

## Technologies all setup and configured and ready to go

1. Node.js
1. TypeScript
1. EsLint (with AirBnb defaults)
1. Yarn
1. Yarn Workspaces (https://classic.yarnpkg.com/blog/2017/08/02/introducing-workspaces/)
1. Jest
1. Cypress
1. TypeDoc.org
1. Prettier
1. Husky

## Scripts

- `yarn` - install (and update minor versions) of all packages
- `yarn start` - Build and Start the project
- `yarn build` - build TypeScript project
- `yarn test` - run unit tests
- `yarn test:watch` - run unit tests while developing
- `yarn test:coverage` - run unit tests but also with code coverage
- `yarn test:cypress` - open cypress automated tests
- `yarn test:cypress:run` - run cypress automated tests (command line only)
- `yarn lint` - run esLint to lint project
- `yarn lint:fix` - run esLint and fix any issues
- `yarn format:prettier` - run Prettier to format project
- `yarn format:prettier:fix` - run Prettier to format project and auto correct
- `yarn docs` - generate docs using TypeDoc
- `yarn release` - Release a semantic version of the project

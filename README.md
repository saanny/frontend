# BitClout Frontend

This is the repository for the reference BitClout Angular app. It serves as an
interface that allows users to interact with the data on the BitClout blockchain.

## Getting started

The Bitclout frontend requires NodeJS.

On MacOS and Linux, install `node` using [Node Version Manager](https://github.com/nvm-sh/nvm#installing-and-updating).

On Windows, download `node` from [nodejs.org](https://nodejs.org/en/download/). You will also need to run: `npm install --global windows-build-tools`

## Development server

Run `npm install` to install all dependencies. Then `npm run start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `npm run generate component component-name` to generate a new component. You can also use `npm run generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

After proper configuration of `environment.ts` and `environment.prod.ts`, run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. Use `npm run build_prod` for a production build.

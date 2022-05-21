# React-Redux Typescript Boilerplate project

## Description:

This boilerplate is meant to avoid using `npx create-react-app`. The reason being that it installs too many unnecessary dependencies & makes your react application bloated. It still includes the same features the `npx create-react-app` command provides you.
This boilerplate includes:

 - React v18
 - Redux Toolkit
 - Typescript
 - Webpack
 - Eslint
 - Prettier
 - Babel

## To-Do list:

 - [ ] Redux & Redux Toolkit addition
 - [ ] Jest integration
 - [ ] Husky integration
 - [ ] Public folder addition
 - [ ] SEO optimization
 - [ ] Proper capturing of Frontend logs (LogRocket)
 - [ ] Example files for project
 - [ ] Dockerfile for optimized docker image

## Installation & Setup guide:

### Dev: `npm run dev`:
This command runs the react application in development mode. You'll notice that the bundle size is proportionally larger than the bundle size in prod. This is due to the amount of dev dependencies.

### Build: `npm run build`:
This will bundle your code for production. It'll be outputted in the build/ folder. After building your React application, go to the build directory and run `npx serve` to serve the production version of your code on your local machine. Note the difference between the bundle sizes.

### Lint: `npm run lint`:
This will check for eslint errors when running. This way you can fix any of them before commiting them. Edit the .eslintrc.js file to change linting rules.

### Format: `npm run format`:
This will check for formatting errors when running the script. It'll auto format the problems depending on the configurations made in the .prettierrc.js file.

## Contributions:

Main contributor: Berkan Alci | Website: www.berkanalci.com

If you want to contribute to this boilerplate, feel free to fork the project & create a PR.

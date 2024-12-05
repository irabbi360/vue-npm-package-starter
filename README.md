# Vue NPM Package Starter

## How to Create and Publish a Vue NPM Package
To create a Vue.js npm package using this repository, simply modify the contents of the lib folder in the root directory. Inside, you'll find an example of a Vue component that you can use as a template for building your own Vue NPM package.

## Test the Library
We can now run `npm run build` and then test out our library. To do this, open up a Vue project (you can open a current Vue 3 project you have, or create a blank one).

## How to Publish to NPM

If you haven't signed into NPM inside your terminal you can do that by running the `npm adduser` command.

Then just run the `npm publish` command and the package should be pushed up and made available on NPM.

## Installation Instructions

`npm i vue-example-npm`

## Usage in Vue.js or Nuxt.js Projects
Once installed, you can import and use the component like this:

`import VueExampleNpm from 'vue-example-npm'`
`import 'vue-example-npm/dist/style.css`
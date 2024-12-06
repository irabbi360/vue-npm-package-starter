# Vue NPM Package Starter

## How to Create and Publish a Vue NPM Package
To create a Vue.js npm package using this repository, simply modify the contents of the lib folder in the root directory. Inside, you'll find an example of a Vue component that you can use as a template for building your own Vue NPM package.

Rename the VueExampleNpm.vue file: Change the filename to match your desired package name. Update the lib/main.ts file: Modify the file to reflect the new package name where necessary. Update the package.json: In the package.json file, replace any occurrence of vue-example-npm with your new package name.

## Test the Library
We can now run `npm run build` and test our library. To do this, open up a Vue project (you can open a current Vue 3 project you have, or create a blank one).

## How to Publish to NPM

If you haven't signed into NPM inside your terminal, you can run the `npm adduser` command.

Then just run the `npm publish` command and the package should be pushed up and made available on NPM.

## Installation Instructions

`npm i vue-example-npm`

## Usage in Vue.js or Nuxt.js Projects
Once installed, you can import and use the component like this:

`import VueExampleNpm from 'vue-example-npm'` <br>
`import 'vue-example-npm/dist/style.css`

# require-local-directory

## How to run

Assuming you have Node.js® and Yarn installed:

1. Clone this repository
2. `cd require-local-directory`
3. `yarn`
4. `node index.js`

## Why is this possible?

The folder `another-test` has a `package.json` file. Per the [documentation](https://docs.npmjs.com/cli/install), we can install from a directory if that directory has that file. It adds a symlink to that folder. This is very handy because we don't need to do symlinking manually whenever our main `node_modules` folder is modified.

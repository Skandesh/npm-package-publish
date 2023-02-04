# npm-package-publish
A demo repo to publish our own npm package

## Usage
Install the package using npm :
 npm install is-null-or-emptyyy --save
Then, require the package and use it:
 [Comment: To check if this usage is proper]
 var isNullOrEmpty = require('is-null-or-emptyyy');
 console.log(isNullOrEmpty("")); // true
 console.log(isNullOrEmpty("Hello World")); // false
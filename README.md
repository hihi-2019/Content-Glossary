# Content-Glossary
## Glossary of Content Covered to Date

### Node JS 
- https://nodejs.org/en/
- 

### npm (node package manager)
- https://www.npmjs.com/
- NPM is a huge registry full of downloadable code modules. We use it to pull down code packages so we can make use of other prewritten functionality, rather than writing things from scratch. 
- To initialise at the start of a project use `npm init -y`
- To install a specifc package use `npm install <package-name>`

### Express 
- https://expressjs.com/
- Node.js module which allows us to set up and run local servers. 
- Use `const express = require('express')` to include in a file.


### fs (file system) 
- https://nodejs.org/api/fs.html
- Node.js module which allows for accessing and manipulating external files. Has both Sync and Asycn built in functions.
- Doesn't need to be installed, comes with node.js
- Use `const fs = require('fs');` to include in a file.

### handlebars 
- https://handlebarsjs.com/
- Node.js module used as a templating language for webpages on the server side, and allows us to extract reusable 'partials'
- Handlebars templates look like regular text with embedded Handlebars expressions e.g `<p>{{firstname}} {{lastname}}</p>`
- To install type `npm install handlebars` in the console
- To use in files type `const hbs = require('handlebars');`
- See Cherise's homework assignment for more details.

### Synchronous Function
- Executes line by line, and prevents the next line of code from executing until the current one has finished executing.

### Asynchronous Function
- Begins executing, and then allows the next line of code to begin executing at the same time. This allows for huge amounts of functionality but can cause issues if the results of an async function are called upon before it has finished executing.

### Callback Functions
- https://guide.freecodecamp.org/javascript/callback-functions/
- Someone else can explain this

### jest
- https://jestjs.io/
- Node.js module used for running tests.
- To install type `npm install jest`
- To use you need to create a `<filename>.test.js` file and then type `npm test <filename>.test.js` in the console.

### superTest 
- https://www.npmjs.com/package/supertest
- Node.js module used for running tests on express servers.
- To install type `npm install supertest`
- Cannot understand parsed objects (from handelbars) unless we party it with Cheerio

### cheerio 
- https://www.npmjs.com/package/cheerio
- Node.js module used for running tests on templated webpages
- To install type `npm install cheerio`







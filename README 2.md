# LAB: API Server

In this lab, you will be fully documenting an API server, with JSDoc, Swagger, UML, and a full suite of tests.

## Requirements

### Technical Writing
* Create a folder called `/docs` at the root of the project
* Create sub-folder under `/docs` called `/config` where you will store your swagger and jsdoc configuration files
* Refer to *Documentation* in the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) to generate jsdocs for this lab.

### JSDoc
This server works great, but isn't very developer friendly at this point. 

* Write documentation for all middleware, models, and modules
* Do not write 'jsdoc' for the routes ...

### Swagger
Now that the server has been upgraded to support dynamic models in the routes using the `/:model` url parameter, we need to revisit our swagger documentation to reflect this.
* The API server includes the [express swagger generator](https://github.com/pgroot/express-swagger-generator) module in the `api` folder to live serve swagger documentation
* Follow the instructions for that library to document your API routes directly in the `api/v1.js` file
* This should auto-generate live swagger live and allow you to fully run and test your API directly in the browser

### Deployment
Get this server deployed to production. Although you aren't writing code against it, your documentation must be accessible through the links in your readme.  
 
### Testing
* Write a complete set of data model and server tests
* Use `supergoose`
* Refer to your previous assigments for examples and inspiration

### Stretch Goal
Deploy this to NPM as an installable module.

## Assignment Submission Instructions
Refer to the the [lab submission instructions](../../../reference/submission-instructions/labs/README.md) for the complete lab submission process and expectations



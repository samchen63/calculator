Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/az400trainingforsam/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_apis/build/status/samchen63.calculator?branchName=refs%2Fpull%2F1%2Fmerge)](https://dev.azure.com/az400trainingforsam/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build/latest?definitionId=10&branchName=refs%2Fpull%2F1%2Fmerge)
The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMicrosoft%2Falmvm%2Fmaster%2Flabs%2Fvstsextend%2Fselenium%2Farmtemplate%2Fazuredeploy.json

https://www.microsoft.com/en-us/download/details.aspx?id=58207&WT.mc_id=rss_alldownloads_extensions

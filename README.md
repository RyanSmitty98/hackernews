## Table of contents
* [Purpose](#Purpose)
* [Setup](#Setup)
* [Tests](#Tests)

## Purpose
This project connects to the Hacker News Api to display a list of stories for the user to be able to view and read.
The current maximum amount of stories avaiable to disaply at a single time is 500,
scrolling down to the bottom will caouse 30 more stories to load up until the maximum of 500 has been reached.

## Setup
To run this project, after downlaoding, navigate to the file and use the "npm start" comand.
It will then load up the hackernews api and allow the user to click on stories that appear.

## Tests
entering the comand 'npm test' will run the tests located in the __test__ folder of the application.
As of current there are 4 tests running right now that all pass.
One thing to note is that when running the tests while they do pass, an error is given to me, it reads:
`waitForElement` has been deprecated. Use a `find*` query (preferred: https://testing-library.com/docs/dom-testing-library/api-queries#findby) or use `waitFor` instead: https://testing-library.com/docs/dom-testing-library/api-async#waitfor

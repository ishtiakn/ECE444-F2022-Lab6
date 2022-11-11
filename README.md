# ECE444-F2022-Lab6
Author: Nissar Ishtiak <br/>
This repo followed instructions from https://github.com/mjhea0/flaskr-tdd.

## Activity 1: FLASKR-TDD
I successfully completed the exercise and deployed my Heroku app: https://sleepy-caverns-94384.herokuapp.com/.

## Activity 2: Adding Test Cases to Project 1 - Education Pathways
I added 3 unit tests to my team's project: https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-1-agility/blob/main/Education_Pathways/backend/tests/course.test.js#L290-L309.<br/><br/>
In case my teammates make edits causing the line numbers to change after I have written this, my tests are tagged with "NISSAR ISHTIAK LAB 6 TDD" in their comments.<br/><br/>
My tests are:<br/>
1) Test that the backend provides a list of all unique course departments in the database when requested.<br/>
2) Test that the backend provides a list of all unique course faculties in the database when requested.<br/>
3) Test that the backend provides a list of all unique course campuses in the database when requested.

## Activity 3: Pros & Cons of TDD
Test Driven Development (TDD) is an approach to software development that interlaces unit testing, programming, and refactoring on the codebase. Here, I discuss its  pros and cons.
### Pros
- Since TDD involves writing small tests often, it forces the development of more modular code which promotes better architecture and also highlights architectural problems earlier.<br/>
- Easier, more conifdent collaboration. People can edit each others code given the safety net of many unit tests to check.<br/>
- All the unit tests being run and created is a safty net that allows for efficient maintenance, updating, and refactoring of code with less risk of breaking the program.<br/>
- Often, when writing tests is scheduled for later, they are delayed and not done as well. TDD forces them to be done before and as code is developed, preventing this issue which means better QA.<br/>
- When writing tests, devs are forced to completely understand all inputs and outputs of functions. This can surface design/architecture/requirements flaws earlier, making them cheaper to fix. <br/>
- More mistakes are caught during development rather than QA, making them cheaper to fix.
### Cons
- TDD makes software development cycle initially slower and more resource intensive. The unit tests need to be planned, developed, and maintained as the project itself is developed. This makes development stage more resource intensive (time and people).<br/>
- Is difficult to learn and master writing/maintaining good unit test suite and the entire team must do this for TDD to work well.<br/>
- Very difficult to apply TDD later on in the development lifecycle, such as to legacy code.<br/>
- Some time tradeoffs. More and more tests make builds slower, but then time also has to be spent refining these tests in order to avoid this.

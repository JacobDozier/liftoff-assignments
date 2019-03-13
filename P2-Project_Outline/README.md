# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
Datasystem Solutions, Inc. would like more automation between the help desk software Zendesk and the time tracking app Harvest. Harvest has a plug in for Zendesk so that it makes Zendesk an all-in-one help desk. Time can be ented in Harvest app that shows on the Zendesk ticket webpage.

Currently, Harvest remebers the last project you were working on. This handy feature is invaluable if you are using the application as intended, we are not. We are using it to track support time against client contracts and need to frequently update which project is selected in Harvest. At the very least, they would like the project to be blanked out so that no one can save time to the wrong project by accident. Ideally, they would be able to click a button and have the current organization in Zendesk populate as the project in Harvest.

Automating the project and task field in Harvest will eliminate user error when entering time against client support contracts. This will save the company money as client generally do not accept errors in time tracking and will not pay for shoddy book keeping. 

### Features
- Reset Harvest Projects: When a zendesk ticket is opened, the Harvest project and task are blanked out.
- Harvest Organization Button: Place a button in the app to look at the organization that reuqested the Zendesk ticket and find the organization in the Harvest Project and populate that value.
- Authentication Token: Obtain and pass authentication token to Harvest based on currently logged in user.

### Technologies
- Zendesk App Tools (ZAT)
- Javascript
- Handlebars.js
- JQuery

### What I'll Have to Learn
I will need to learn how to use Zendesk's and Harvest's api's to read and mainpulate ticket/Harvest states.

I will also need to learn the basics of Javascript, JQuery, Handlebars.js and the ZAT.

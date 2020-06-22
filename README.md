# React JS Landing Page Web App Template

## Overview
The goal is to improve SEO with react but does the __meteor js__ result in any drawbacks?
- See 
    1. Limitations of Meteor.js
    2. See your playlist "React" with the topic to improve SEO.


### <a href="https://react-landing-page-template.herokuapp.com">LIVE DEMO</a> 

## Description
This is a ReactJS based landing page template, fit for a startup company/service with a one page view. The design is inspired by a template from <a href="https://www.free-css.com/assets/files/free-css-templates/preview/page234/interact/">Free-CSS.com </a>
All componenets data can be easily modified to git use by changing the data.JSON file that contains all data.

## Make it Yours!
### 1. Preps
You will need to have <a href="meteor.com">Meteor JS </a> as well as <a href="https://nodejs.org/">Node JS</a> installed on your pc. 

### 2. Clone Files
After cloning the files, you will have to run ```npm install``` followed by ```meteor``` in the CLI
### 3. Add your own data 
Change the data in the ```data.JSON``` file as well as add any images to ```public/img/```
You can also change styles by modifying the ```public/css``` files.


## Credits
##### Free CSS 
<a href="https://www.free-css.com/assets/files/free-css-templates/preview/page234/interact/">Free-CSS.com </a>

##### Issaaf kattan


## Customizing this website
### Customize route
- We have one route that is defined in ./imports/routes/router.jsx that imported App.js

### Customize front page
- We have all the components in ./imports/frontend/ 

### Data rendered 
- All the data is rendered from ./public/data.json that is loaded by getResumeData() in imports/frontend/APP.jsx

### Progress
1. change the ./public/css/style.css. Create a root containing all (primary, secondary...) colors within a variable to easy customization.
2. Define the design structure

[![Build Status](https://travis-ci.org/shapeable/prototype-web.svg?branch=master)](https://travis-ci.org/shapeable/prototype-web)
[![Code Climate](https://codeclimate.com/github/shapeable/prototype-web/badges/gpa.svg)](https://codeclimate.com/github/shapeable/prototype-web)
[![Test Coverage](https://codeclimate.com/github/shapeable/prototype-web/badges/coverage.svg)](https://codeclimate.com/github/shapeable/prototype-web/coverage)

# prototype-adpq
Version 1.0 03/03/2017

#### Table of Contents
- PROTOTYPE URL
- OVERVIEW
- INSTALLATION
- DOCUMENTATION
- CONTACT INFO
- COPYRIGHT

## PROTOTYPE URL

# OVERVIEW
The website and mobile app are platforms that notify residents of different regions in California on emergencies happening near them. The platform is focused on two main users: The Government administrator and the californian resident.
Government administrator user features include: a dashboard where the administrator may publish alerts, force alerts when needed, and analyze visually the generated notifications data.
Resident user features include: creating a profile where he/she can choose how to be notified, on the alerts he/she wants to track by filling in a small survey to propose alerts of his/her interest.

The prototype was created by following the playbooks provided as a guide, with the help of tools of user centered design methodology which included regular feedback on the prototype in every stage developed. The prototype was also done following the agile development currently used in our company for all our products. This practices are reflected and detailed within this document.


# INSTALLATION

# TECHNICAL APPROACH
A more comprehensive description of our Technical Approach can be found [here]() 

#### A. Assigned a team leader
Alan Mond, Product Owner

#### B. Team Members (and corresponding ADPQ labor categories)
+ Product Manager: Diana D´Herrera
+ Technical Architect: Rafael Cárdenas
+ Interaction Designer/User Researcher: Diana D´Herrera
+ Visual Designer: Sofía Moya
+ Front End Developer: Isabel Anguiano 
+ Back End Developer: Miguel Morán
+ Dev Ops Engineer: Giovanni Cortés
+ Security Engineer: Rafael Cárdenas
+ Agile Coach: Paulina Bustos
+ Quality Assurance: Juan Pablo Escobar

#### C. Understood what people needed.

User research and testing was divided in three main methods present in human-centered design creative approach:

Inspiration phase
+ Research of other platforms that offered similar solutions.
+ Initial interviews with potential users - [Link to interviews](https://github.com/shapeable/prototype-               web/blob/technical_approach/supporting-documents/Initial%20iterview%20questions.xlsx).
+ Framing the design challenge - [Link](https://github.com/shapeable/prototype-web/blob/master/supporting-documents/Framing%20your%20design%20challenge.pdf)

Ideation phase
+ Downloading all the insights recollected from the interviews and forms.
+ Team meetings for Brainstorm sessions.
+ Definition of an initial core features list and a customer journey.

Implementation
+ Creation of Mock ups - [Link](https://github.com/shapeable/prototype-web/blob/master/supporting-documents/Costumer%20Journey%20mock%20ups.pdf)
+ Initial mock ups reviewed with unassociated staff member to provide additional feedback on application behavior - [Link](https://github.com/shapeable/prototype-web/blob/master/supporting-documents/Prototype%20mock%20ups.pdf)
+ Initial [wireframes](https://invis.io/6VAJF25EK) were tested by potential government and resident users. The design of the tests included 4 main tasks. - [Link to user testing](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)
+ Changes from former feedback were incorporated to design a final prototype which was tested again in another focus group for validation. The design of the tests included 4 main tasks. - [Link to user testing](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)


#### D. Used at least three “human-centered design” techniques or tools
Multiple human-centered design techniques were used in the development of the prototype.
These included:
+ Creative approach: Inspiration, Ideation and Implementation.
+ Creation of wireframes in Invision - [Link to Wireframes](https://invis.io/6VAJF25EK)
+ Creation of "user stories" in Github issues  - [Link to user stories](https://github.com/shapeable/prototype-web/blob/master/supporting-documents/Userstories.pdf) 
+ Creating a Product Backlog list of prioritized "user stories" - Link to product backlog screenshot
+ Design style guide. The official US digital services playbook was used as a reference https://playbook.cio.gov/  - Link to the guide
+ Usability testing of wireframes - [Link to user testing](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)
+ Usability testing of prototypes - [Link to user testing](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)

#### E. Used GitHub to document code commits

GitHub was used as the main documentation tool.  User Stories were created under the Issues to create a Product Backlog, a Project was generated to keep track of progress and all commits and comments were stored in the same repository.  All design decision history has been documented in the repo. - [Link to the master commits record](https://github.com/shapeable/prototype-web/commits/master) .

#### F. Used Swagger to document the RESTful API, and provided a link to the Swagger API

#### G. Complied with Section 508 of the Americans with Disabilities Act and WCAG 2.0

#### H.Created or used a design style guide

A style guide was created by the UI designer with all the design elements present in the prototype. (Download style guide)

#### I. Performed usability tests with people

Usability tests were done in every step of the process.

+ Testing of initial concepts - [Link to interviews](https://github.com/shapeable/prototype-               web/blob/technical_approach/supporting-documents/Initial%20iterview%20questions.xlsx).
+ Testing of initial [wireframes](https://invis.io/6VAJF25EK) - [Link to user testing tasks and interviews](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)
+ Testing of final prototype - [Link to user testing tasks and interviews](https://github.com/shapeable/prototype-web/tree/master/supporting-documents/user-testing)

Insights:
Wireframe testing sugestions
Prototype testig suggestions

#### J. Used an iterative approach, where feedback informed subsequent work or versions of the prototype

Our iterative approach worked as follows:
+ Set up team collaboration in Slack
+ Use of SCRUM methodology
+ Set up of sprints and daily standups
+ Regular team demos for feedback
+ Fast iteration in the design process as feedback was given
+ Single sprint for development
+ Review by Product Owner

#### K. Created a prototype that works on multiple devices and presents a responsive design

Our solution utilizes fluid grids that respond to most common desktop screen and devices, allowing flexible images and text resizing to present the best render according to each device.
We provide a clean interface which is compatible with most common web browsers and looks great in mobile devices.

The core of the responsiveness can be reviewed in these sections:
+ The grid - (4 tailored layouts)
https://github.com/shapeable/prototype-web/blob/master/web-app/app/assets/stylesheets/base/_grid_settings.scss
+ Fluid columns
https://github.com/shapeable/prototype-web/blob/master/web-app/app/assets/stylesheets/base/_cols.scss

#### L. Used at least five modern and open-source technologies

This is a list of the open-source technologies and the use given for the creation of the prototype.
+ Docker - Production deployment
+ Swagger - Documentation of the API
+ Ruby on rails - Back end development
+ Rspec - Test
+ PostgreSQL - Database
+ Bourbon (for SCSS) - Style sheets


#### M. Deployed the prototype on PaaS

The prototype is deployed on a Heroku server which allows for quick deployments and all hardware updates and maintenance provided by Heroku.  Additionally many services such as continuous monitoring are native add-ons that further simplify implementation and maintenance.

#### N. Developed automated unit tests

After creating unit tests for each feature or functionality, rspec was used as the automated unit tester.  For example to test SMS (text messages) functionality, a specific unit test was created for that purpose: (Send SMS Messages code)[https://github.com/shapeable/prototype-web/blob/master/web-app/spec/modules/send_sms_messages_spec.rb]

Other Unit tests can be found under: (https://github.com/shapeable/prototype-web/tree/master/web-app/spec/modules)[https://github.com/shapeable/prototype-web/tree/master/web-app/spec/modules]

#### O. Setup or used a continuous integration system to automate the running of tests

We used Travis CI (Continuous Integration) server to run automated tests every time code was deployed to our Heroku instance.  Travis CI is linked directly to the GitHub repo so it checks it automatically for any errors before being merged and deployed to production.

#### P. Setup or used configuration management

#### Q. Setup or used continuous monitoring

[Rollbar](https://www.rollbar.com) was implemented as the continuous monitoring tool.  Rollbar can be quickly added to any Ruby application as a gem and is also a standard add-on for Heroku deployments.  It has a notification system built in that immmediately alerts the team if there are any errors.

#### R. Deployed their software in an open source container
This project is deployed using Docker container technology. Some of the advantages of using Docker are:
* Simplifying Configuration
* Code pipeline management
* Developer Productivity
* App Isolation
* Server Consolidation
* Debugging Capabilities
* Multi-tenancy
* Rapid Deployment

#### S. Provided sufficient documentation to install and run their prototype on another machine

The README.md file written in the repository contains complete instructions for deploying and running the prototype on any computer. The instructions are divided by front end and back end requirements and can be found here]. ()

#### T. Prototype and underlying platforms used to create and run the prototype are openly licensed and free of charge


#### Examples of U.S. Digital Playbook usage

# CONTACT INFO

Shapeable
2120 University Ave
Berkeley, CA 94704
c:  510-662-6152


# COPYRIGHT

Copyright 2017 [Shapeable](https://www.shapeable.net/). All rights reserved



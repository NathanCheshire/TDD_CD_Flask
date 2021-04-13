# Homework 3 and 4 for software QA

## Dates:
Started: 3/27/21

Finished: 4/12/21

## Due: 
April 16, Midnight

## Objective:
Develop testing and deployment plans that enable continuous deployment of an existing
software system that is extended for web access. Create automated acceptance tests (end-to-end
testing) and integration (regression) tests.

## Scenario:
You have been asked to create a web interface for the application you created for Assignment2. The VP of Engineering at your firm also wants to ensure that you can continuously deploy
new features, bug fixes, and changes to the application. She also wants to ensure the quality of
the overall system by adopting a quality assurance and test plan.
You will augment the existing application and make it accessible via a web interface and build
& document a deployment pipeline for the system using various tools and cloud infrastructure.

## Requirements.
Web Interface - Add a web interface to your command line app and make it accessible via the
Google Cloud Platform (e.g., container engine [vm], Google App Engine, etc.).

Deployment Pipeline - Setup a deployment pipeline using continuous integration and delivery
tools (can make your GitHub project public).

## Features of my app
unit testing in python with unittest - these are automatically ran with github actions on push to github

code coverage - TODO

continuous deployment to heroku - upon a push, herou will wait for the unittests to pass, if they pass, it will then deploy the new app to the server

# Hapless Friend Finder


## Description

An app to find you a friend that is psychologically copatible.   Take the quiz and see who best suites you.


*Hapless Friend Finder* implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.

*Hapless Friend Finder* application is meant to simulate a simple dating app. The application is implemented using a [Node.js](https://nodejs.org/en/) and [Express](https://expressjs.com/) server on the back end and the [Materialize](http://materializecss.com/) CSS framework on the front end.

## Demo
	
*Friend Finder* is deployed to Heroku. Please check it out [here](https://heroku.com/mighty-cliffs-34800.git
).

## Installation

To install the application follow the instructions below:

	git clone git@github.com:anibogo7/haplessfriendfinder.git
	cd friend-finder
	npm install
	
## Running Locally

To run the application locally and access it in your browser, run the Node.js application with the command below.

	node server.js
	
The application will now be running locally on `PORT`, Usually localhost:8080 but may be different. You can then access it locally from your browser at the URL, in this case `localhost:8080`.
## Description

This application implements friend matching from responses to a ten question survey. The application is meant to simulate a simple dating app. The application is implemented using a Node.js and Bootstrap framework on the front end.
*Friend Finder* implements friend matching based on the user's responses to a ten question survey. The user responds to questions with values from 1 to 5 characters. When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all ten questions combined.

More coming soon!
*Friend Finder* application is meant to simulate a simple dating app. The application is implemented using a [Node.js](https://nodejs.org/en/).


## Installation

To install the application follow the instructions below:

	git clone https://github.com/sammypaiz0606/friend_finder.git
	cd friend_finder
	npm install

## Example

<img src='app/img/seinfield_1.jpg' width='900' height='800'>
<img src='app/img/seinfield_2.jpg' width='900' height='800'>
<img src='app/img/seinfield_3.jpg' width='900' height='800'>
## Running Locally

To run the application locally and access it in your browser, first set the `PORT` environment variable to the value of your choice. An example is shown below.

	export PORT=3002

After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js

The application will now be running locally on `PORT`, in this case that is port 3030. You can then access it locally from your browser at the URL `localhost:PORT`, in this case `localhost:3002`.

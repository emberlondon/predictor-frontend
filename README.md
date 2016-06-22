# Predictor

EmberLondon Project Night of Thursday, 16th of June 2016, Hosted by and at **[ShowMyHomework](https://www.showmyhomework.co.uk)**.  
Football Predictor game. Based on **[BBC's football predictor]( http://www.bbc.co.uk/sport/football/predictor)**.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone https://github.com/emberlondon/predictor-frontend.git` this repository
* `cd predictor-frontend`
* `npm install`
* `bower install`

## Additional Installations

The app has a custom api which you can download here:
https://github.com/emberlondon/predictor-api

## Running / Development

Before running the app, you will have to complete the installation of the custom api.

* `ember server --proxy=http://localhost:3000`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Running Tests

* `ember test`

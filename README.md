### Setup

##### Prerequisites

Install Node.js, which brings npm package manager.

Install [polymer-cli](https://github.com/Polymer/polymer-cli):

    npm install -g polymer-cli

##### Initialize project from template

    mkdir my-app
    cd my-app
    polymer init starter-kit

### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve --open

### Bower
	
	npm install -g bower
	bower update --save
	bower install --save PolymerElements/paper-slider


### Build

    polymer build

### Deploy to app engine

	python "D:\Courses\Hackathon\google-cloud-sdk\platform\google_appengine\appcfg.py" -A bootcamp-cconti update app.yaml
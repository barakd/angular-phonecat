# AngularJS Phone Catalog Fork (AngularJS 1.4 version)

## Overview
A fork of Angularjs Phone Catalog, based on it 1.4 version.
From the AngularJS [tutorial]( http://docs.angularjs.org/tutorial)
Used it for my talk "[From MVC to Component Based Architecture](https://www.youtube.com/watch?v=JlyEZf4vBBY&feature=youtu.be)",
As an example of how we used to write AngularJS application in MVC style.

### Running the app during development
Make sure you run once

```
npm install
```
then anytime to run the app:
- Run `npm start`
- navigate your browser to `http://localhost:8000/app/index.html` to see the app running in your browser.

## Application Directory Layout

    app/                --> all of the files to be used in production
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      index.html        --> app layout file (the main html template file of the app)
      js/               --> javascript files
        app.js          --> the main application module
        controllers.js  --> application controllers
        directives.js   --> application directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
        animations.js   --> hooks for running JQuery animations with ngAnimate
      partials/         --> angular view partials (partial html templates) used by ngRoute
        partial1.html
        partial2.html
      bower_components  --> 3rd party js libraries, including angular and jquery

    scripts/            --> handy scripts
      update-repo.sh       --> pull down the latest version of this repos
                               (BE CAREFUL THIS DELETES ALL CHANGES YOU HAVE MADE)
      private/             --> private scripts used by the Angular Team to maintain this repo
    test/               --> test source files and libraries
      karma.conf.js        --> config file for running unit tests with Karma
      protractor-conf.js   --> config file for running e2e tests with Protractor
      e2e/
        scenarios.js       --> end-to-end specs
      unit/             --> unit level specs/tests
        controllersSpec.js --> specs for controllers
        directivesSpec.js  --> specs for directives
        filtersSpec.js     --> specs for filters
        servicesSpec.js    --> specs for services

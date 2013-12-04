Getting started with Karma project files to accompany blog post:

http://kroltech.com/2013/11/javascript-tdd-with-jasmine-and-karma/

Dependencies:

$ npm install -g karma

$ npm install -g phantomjs


To run Karma tests:

$ karma start karma.conf.js

(will run in autowatch mode)

For single run test:

$karma start karma.conf.js --single-run --browsers PhantomJS

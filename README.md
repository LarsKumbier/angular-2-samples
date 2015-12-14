AngularJS 2@alpha-52 Samples
============================

Live DEMO here: http://www.syntaxsuccess.com/angular-2-samples
Documentation:  http://www.syntaxsuccess.com/viewarticle/angular-2.0-examples

The project uses TypeScript, so to get started you may have to run the following:

1. Install the TypeScript compiler: `npm install -g typescript@^1.7.0`
2. Run `npm install` and `bower install`

These steps take care of installing required tooling - the final step is to start the TypeScript compiler to transpile your TypeScript code to JavaScript.

I like to run it as a watch in order to automatically regenerate whenever I change my TypeScript.
Use the following command to start watching your files and a webserver:

`npm start`

The above steps will build all dependencies, so all you have to do now is open your browser: http://127.0.0.1:10808.
Alternatively, you can use any type of webserver you want since it's just a static html page. I generally do it from Webstorm by right clicking
`index.html` and selecting `Run index.html`.

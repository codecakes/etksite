# Etksite readme

## Description

Official Home of Project Etk using the Non-commercial Opensource framework built ontop of Colored Coins using COLU SDK.

Etk is a project based on Colored Coins using COLU SDK. It is intended to be a blockchain framework consisting of:

    Currency like Token operations
    Security Operations
    Trade sequencing

It is A thin wrapper to create standard token functions that can be used to build any token based Digital Currency with Contract details embedded as Smart Contracts. Among others, Goal is to have a Standardized Release Candidate proposal that can be improvised later on.

Check out the official documentation for more details on how to start using it and goals:
https://codecakes.gitbooks.io/etk/content/


## Technologies used

JavaScript
- [Browserify](http://browserify.org/) with ES6/2015 support through [Babel](https://babeljs.io/)
- [Node](https://nodejs.org/)

Styles
- [Stylus](https://learnboost.github.io/stylus/)

Markup
- [Jade](http://jade-lang.com/)

Optimization
- [Imagemin](https://github.com/imagemin/imagemin)
- [Uglify](https://github.com/mishoo/UglifyJS)

Server
- [BrowserSync](http://www.browsersync.io/)

Linting
- [ESlint](http://eslint.org/)

Automation
- [Gulp](http://gulpjs.com)

Code Management
- [Editorconfig](http://editorconfig.org/)
- [Git](https://git-scm.com/)


## Automated tasks

This project uses [Gulp](http://gulpjs.com) to run automated tasks for development and production builds.
The tasks are as follows:

`gulp --production`: Same as `gulp serve --production` also run `gulp test` and  not boot up production server

`gulp serve`: Compiles preprocessors and boots up development server
`gulp serve --open`: Same as `gulp serve` but will also open up site/app in your default browser
`gulp serve --production`: Same as `gulp serve` but will run all production tasks so you can view the site/app in it's final optimized form

`gulp test`: Lints all `*.js` file in the `source` folder using eslint

***Adding the `--debug` option to any gulp task displays extra debugging information (ex. data being loaded into your templates)***

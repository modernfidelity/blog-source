+++
author = ""
categories = ["Javascript", "Angular 2"]
date = "2016-09-16T17:32:36+01:00"
description = ""
featured = ""
featuredalt = ""
featuredpath = ""
linktitle = ""
title = "angular2 universal webpack"
type = "post"

+++

## Notes from first experiments Angular2

The following are some useful snippets on the new javascript code setup for Angular 2. The basis of 
the application is the around the 'isomorphic' server-side rendering known as 'Universal' and the tool 
set of Webpack over the traditional Grunt/Gulp.

Link to the main boiler plate for Universal [https://github.com/angular/universal-starter](https://github.com/angular/universal-starter)

### Angular 2

    npm install -g angular-cli
    npm install -g webpack
    npm install -g typescript

Then you can create a new application with the following : 

    ng new snazzy-js-project
    cd snazzy-js-project
    ng serve
   
Open http://localhost:4200 in your browser.

### Webpack

Introduction from the Angular Docs : [https://angular.io/docs/ts/latest/guide/webpack.html](https://angular.io/docs/ts/latest/guide/webpack.html)

Good podcast on 'Webpack' and Angular2 : [http://podplayer.net/#/?id=15461508](http://podplayer.net/#/?id=15461508)

When to use and why ? [http://blog.andrewray.me/webpack-when-to-use-and-why/](http://blog.andrewray.me/webpack-when-to-use-and-why/)
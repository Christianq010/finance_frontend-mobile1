# Finance App - Mobile Mockup Sketch Design to Webpage 
This project is a mockup Sketch project turned into a webpage optimized for a mobile experience. The Mockup was created on Sketch. Please view the deployed link on a mobile device for an optimal viewing experience. 

Tools used to aid the Front-end work were [Zeplin](https://zeplin.io/), Chrome Dev Tools for testing and NPM and Gulp for compiling [SASS](http://sass-lang.com/) and running a dev server and managing bower dependencies.

## Mockup Preview

[![Mockup Preview](https://preview.ibb.co/j78NxG/finance_mobile.png)](https://ibb.co/ei4vHG)

The project file for this Sketch Mockup can be found [here](https://www.sketchappsources.com/free-source/949-boa-mobile-banking-app-sketch-freebie-resource.html)


## Usage
> This project was started by cloning the following [starter project](https://github.com/Christianq010/sass_starter_pack). It is a basic template for turning HTML5 templates on the web into projects I can edit with SASS and JS dependencies handled via bower.


### Deployed
Deployed via [Surge](https://surge.sh/) at https://finance-mobile.surge.sh/


## Installation

### [NPM](https://docs.npmjs.com/cli/install)
* Install the dependencies after cloning this project (gulp, gulp-sass, browser-sync)

```sh
$ npm install
```

### Bower
* Run `bower install`

### Run Server
This will watch your sass files, compile them and run your dev server at http://localhost:3000

```sh
$ npm start
```

### Troubleshooting
#### The `node-sass` Error
* Delete the `node_modules` folder installed via `npm install`
* Install node dependencies with `yarn install`
* Run `npm rebuild node-sass`
* Run with `gulp`.

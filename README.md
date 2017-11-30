# Template Starter Pack
A light package for compiling Sass and running a dev server and managing bower dependencies from free HTML5 on the web.

# [Start Bootstrap - 2 Col Portfolio](https://startbootstrap.com/template-overviews/2-col-portfolio/)

[2 Col Portfolio](https://startbootstrap.com/template-overviews/2-col-portfolio/) is a two column portfolio layout template for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).

## Preview

[![2 Col Portfolio Preview](https://www.photobox.co.uk/my/photo/full?photo_id=500284169719)](https://blackrockdigital.github.io/startbootstrap-2-col-portfolio/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-2-col-portfolio/)**


## Usage
> This project is a basic template for turning HTML5 templates on the web into projects I can edit with SASS and js dependencies handled via bower.

> Also contains a few points on bower and npm as a refresher for me when initilizing a Front End project.

### Deployed
Deployed via [Surge](https://surge.sh/) at http://surge-global-salary-1.surge.sh/

### Version
1.0.0

## Installation

### [NPM] (https://docs.npmjs.com/cli/install)
* To start a package.json use `npm init`
* Install packages by using `npm install gulp-sass gulp browersync` etc.
* Use `-D, --save-dev` and the Package will appear in your `devDependencies`.
* Install the dependencies after cloning this project (gulp, gulp-sass, browser-sync)

```sh
$ npm install
```

### Bower
* Initialize bower with `bower init`
* Install a bower package and update `.json` with `bower install bootstrap -S`
* Install any github url with `bower install url`
* [Bower installer] (https://github.com/rquadling/bower-installer) provides an easy way for the main files to be installed or moved to one or more locations. Simply add to your `bower.json` an install key and path attribute:

```
{
    "name": "test",
    "version": "0.1",
    "dependencies": {
        "backbone": "latest"
    },
    "install": {
        "path": "some/path",
        "sources": {
            "requirejs": "bower_components/requirejs/require.js"
        }
    }
}
```

### Run Server
This will watch your sass files, compile them and run your dev server at http://localhost:3000

```sh
$ npm start
```

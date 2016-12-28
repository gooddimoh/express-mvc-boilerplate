﻿Express MVC Boilerplate
==================================
[![License](http://img.shields.io/:license-mit-blue.svg)](https://opensource.org/licenses/MIT)

> A simple mvc boilerplate for express.js (gulp + expressjs + nodemon + browser-sync)

## Related modules

* express - web application framework for node
* pug - template engine
* stylus - pre-processor CSS
* mongoose - nodejs orm for mongodb
* bower - a package manager for the web
* gulp - automate workflow

## Prerequisites
* Node.js `http://nodejs.org`
* MongoDB `brew install mongodb`

## Project Structure
```
.
├── app/
│   └── controllers           = contains controller files
│   └── models                = contains model files
│   └── views                 = contains express view (pug) files
│   └── routes.js             = routes config file
├── config/
│   ├── index.js              = environment config file
│   └── db.js                 = db config
├── public/                   = contains static assets
│   ├── components            = bower components folder
│   │   └── ...
│   ├── favicon               = favicon folder
│   ├── fonts                 = contains font files
│   ├── css                   = all files will generate from gulp
│   ├── styl                  = contains style sheets (stylus)
│   ├── js                    = contains js files
│   └── img                   = contains image files
├── test/
│   └── spec.js               = unit & func tests
├── .bowerrc                  = bower config
├── .bower.json               = bower dependencies
├── .Procfile                 = process file for heroku implementation
├── .gitignore                = specifies intentionally untracked files to ignore
├── .editorconfig.js          = editor config
├── .gulpfile.js              = gulp config
├── app.js                    = app setup file
└── package.json              = build scripts and dependencies

```

## Getting Started

```
The easiest way to get started is to clone the repository:

# Get the latest snapshot
$ git clone https://github.com/oguzhanoya/express-mvc-boilerplate.git myproject
$ cd myproject

# Install dependencies
$ npm install

$ bower install

$ node app.js
```

## Development

    gulp

## Test

    npm test

## License

MIT

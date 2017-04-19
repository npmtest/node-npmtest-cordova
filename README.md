# npmtest-cordova

#### basic test coverage for  cordova (v6.5.0)  [![npm package](https://img.shields.io/npm/v/npmtest-cordova.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cordova) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cordova.svg)](https://travis-ci.org/npmtest/node-npmtest-cordova)

#### Cordova command line interface tool

[![NPM](https://nodei.co/npm/cordova.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cordova)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cordova/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cordova/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cordova/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cordova/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cordova/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cordova/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cordova/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cordova/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cordova/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cordova/build/test-report.html](https://npmtest.github.io/node-npmtest-cordova/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cordova/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cordova/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cordova/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cordova/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cordova/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "cordova",
    "version": "6.5.0",
    "preferGlobal": "true",
    "description": "Cordova command line interface tool",
    "main": "cordova",
    "engines": {
        "node": ">=4.0.0"
    },
    "bin": {
        "cordova": "./bin/cordova"
    },
    "scripts": {
        "test": "npm run jshint && npm run jasmine",
        "jshint": "jshint spec && jshint src",
        "cover": "istanbul cover --root src --print detail jasmine",
        "jasmine": "jasmine --captureExceptions --color"
    },
    "repository": {
        "type": "git",
        "url": "https://git-wip-us.apache.org/repos/asf/cordova-cli.git"
    },
    "bugs": {
        "url": "https://issues.apache.org/jira/browse/CB"
    },
    "keywords": [
        "cordova",
        "client",
        "cli"
    ],
    "dependencies": {
        "cordova-common": "2.0.0",
        "cordova-lib": "6.5.0",
        "insight": "~0.8.2",
        "nopt": "3.0.1",
        "q": "1.0.1",
        "underscore": "1.7.0",
        "update-notifier": "^0.5.0"
    },
    "devDependencies": {
        "jasmine": "^2.5.2",
        "istanbul": "^0.4.5",
        "jshint": "^2.9.4"
    },
    "author": {
        "name": "Anis Kadri"
    },
    "contributors": [
        {
            "name": "Brian LeRoux"
        },
        {
            "name": "Fil Maj"
        },
        {
            "name": "Mike Reinstein"
        },
        {
            "name": "Darry Pogue"
        },
        {
            "name": "Michael Brooks"
        },
        {
            "name": "Braden Shepherdson"
        },
        {
            "name": "Gord Tanner"
        },
        {
            "name": "Tim Kim"
        },
        {
            "name": "Benn Mapes"
        },
        {
            "name": "Michael Wolf"
        },
        {
            "name": "Andrew Grieve"
        },
        {
            "name": "Bryan Higgins"
        },
        {
            "name": "Don Coleman"
        },
        {
            "name": "Germano Gabbianelli"
        },
        {
            "name": "Ian Clelland"
        },
        {
            "name": "Lucas Holmqust"
        },
        {
            "name": "Matt LeGrand"
        },
        {
            "name": "Michal Mocny"
        },
        {
            "name": "Sam Breed"
        },
        {
            "name": "Tommy-Carlos Williams"
        },
        {
            "name": "Rubén Norte"
        },
        {
            "name": "Germano Gabbianelli"
        },
        {
            "name": "Steven Gill"
        },
        {
            "name": "Jesse"
        }
    ],
    "license": "Apache-2.0",
    "dist": {
        "shasum": "e6ec81b17dd50c17c40b4b87330f7ced38fb0b47",
        "tarball": "https://registry.npmjs.org/cordova/-/cordova-6.5.0.tgz"
    },
    "maintainers": [
        {
            "name": "agrieve"
        },
        {
            "name": "anis"
        },
        {
            "name": "apachebuilds"
        },
        {
            "name": "bennmapes"
        },
        {
            "name": "bhiggins"
        },
        {
            "name": "bowserj"
        },
        {
            "name": "brianleroux"
        },
        {
            "name": "cmarcelk"
        },
        {
            "name": "filmaj"
        },
        {
            "name": "kamrik"
        },
        {
            "name": "kotikov.vladimir"
        },
        {
            "name": "mmocny"
        },
        {
            "name": "mwbrooks"
        },
        {
            "name": "purplecabbage"
        },
        {
            "name": "sgrebnov"
        },
        {
            "name": "shazron"
        },
        {
            "name": "shepheb"
        },
        {
            "name": "stevegill"
        },
        {
            "name": "timbarham"
        }
    ],
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

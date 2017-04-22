# npmtest-grunt-simple-mocha

#### basic test coverage for  [grunt-simple-mocha (v0.4.1)](https://github.com/yaymukund/grunt-simple-mocha)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-simple-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-simple-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-simple-mocha.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-simple-mocha)

#### A simple wrapper for running tests with Mocha.

[![NPM](https://nodei.co/npm/grunt-simple-mocha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-simple-mocha)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-simple-mocha/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-simple-mocha/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-simple-mocha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-simple-mocha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-simple-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-simple-mocha/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-simple-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-simple-mocha",
    "description": "A simple wrapper for running tests with Mocha.",
    "version": "0.4.1",
    "homepage": "https://github.com/yaymukund/grunt-simple-mocha",
    "author": {
        "name": "Mukund Lakshman",
        "url": "http://yaymukund.com"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/yaymukund/grunt-simple-mocha.git"
    },
    "bugs": {
        "url": "https://github.com/yaymukund/grunt-simple-mocha/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/yaymukund/grunt-simple-mocha/blob/master/LICENSE-MIT"
        }
    ],
    "main": "grunt.js",
    "bin": "bin/grunt-simple-mocha",
    "engines": {
        "node": "*"
    },
    "scripts": {
        "test": "node_modules/mocha/bin/mocha tests/acceptance-tests.js"
    },
    "dependencies": {
        "mocha": "*"
    },
    "devDependencies": {
        "grunt": "0.4.x",
        "grunt-contrib-jshint": "0.1.x",
        "mocha": "^2.3.4"
    },
    "keywords": [
        "gruntplugin",
        "mocha",
        "test"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

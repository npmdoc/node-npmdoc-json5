# npmdoc-json5

#### api documentation for  [json5 (v0.5.1)](http://json5.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-json5.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-json5) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-json5.svg)](https://travis-ci.org/npmdoc/node-npmdoc-json5)

#### JSON for the ES5 era.

[![NPM](https://nodei.co/npm/json5.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json5)

- [https://npmdoc.github.io/node-npmdoc-json5/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json5/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json5/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json5/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-json5/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-json5/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aseem Kishore"
    },
    "bin": {
        "json5": "lib/cli.js"
    },
    "bugs": {
        "url": "https://github.com/aseemk/json5/issues"
    },
    "contributors": [
        {
            "name": "Max Nanasy"
        },
        {
            "name": "Andrew Eisenberg"
        },
        {
            "name": "Jordan Tucker"
        }
    ],
    "dependencies": {},
    "description": "JSON for the ES5 era.",
    "devDependencies": {
        "gulp": "^3.9.1",
        "gulp-jshint": "^2.0.1",
        "jshint": "^2.9.3",
        "jshint-stylish": "^2.2.1",
        "mocha": "^3.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1eade7acc012034ad84e2396767ead9fa5495821",
        "tarball": "https://registry.npmjs.org/json5/-/json5-0.5.1.tgz"
    },
    "files": [
        "lib/"
    ],
    "gitHead": "6be6a70e250e6fbbf42db75cd1f6a1aadeeeeb07",
    "homepage": "http://json5.org/",
    "keywords": [
        "json",
        "es5"
    ],
    "license": "MIT",
    "main": "lib/json5.js",
    "maintainers": [
        {
            "name": "aseemk"
        },
        {
            "name": "jordanbtucker"
        }
    ],
    "name": "json5",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aseemk/json5.git"
    },
    "scripts": {
        "build": "node ./lib/cli.js -c package.json5",
        "test": "mocha --ui exports --reporter spec"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

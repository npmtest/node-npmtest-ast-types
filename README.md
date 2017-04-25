# npmtest-ast-types

#### basic test coverage for  [ast-types (v0.9.11)](http://github.com/benjamn/ast-types)  [![npm package](https://img.shields.io/npm/v/npmtest-ast-types.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ast-types) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ast-types.svg)](https://travis-ci.org/npmtest/node-npmtest-ast-types)

#### Esprima-compatible implementation of the Mozilla JS Parser API

[![NPM](https://nodei.co/npm/ast-types.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ast-types)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ast-types/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ast-types/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ast-types/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ast-types/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ast-types/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ast-types/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ast-types/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ast-types/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ast-types/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ast-types/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ast-types/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ast-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ast-types/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ast-types/build/test-report.html](https://npmtest.github.io/node-npmtest-ast-types/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ast-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ast-types/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ast-types/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ast-types/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ast-types/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ast-types/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ast-types/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ast-types/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Newman"
    },
    "bugs": {
        "url": "https://github.com/benjamn/ast-types/issues"
    },
    "dependencies": {},
    "description": "Esprima-compatible implementation of the Mozilla JS Parser API",
    "devDependencies": {
        "babel-types": "^6.23.0",
        "babylon": "^6.16.1",
        "espree": "^3.1.7",
        "esprima": "~3.1.3",
        "esprima-fb": "~14001.1.0-dev-harmony-fb",
        "mocha": "~3.2.0",
        "reify": "^0.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "371177bb59232ff5ceaa1d09ee5cad705b1a5aa9",
        "tarball": "https://registry.npmjs.org/ast-types/-/ast-types-0.9.11.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "0d84f3ca644aea33bb7892c4c7b570deb999c73d",
    "homepage": "http://github.com/benjamn/ast-types",
    "keywords": [
        "ast",
        "abstract syntax tree",
        "hierarchy",
        "mozilla",
        "spidermonkey",
        "parser api",
        "esprima",
        "types",
        "type system",
        "type checking",
        "dynamic types",
        "parsing",
        "transformation",
        "syntax"
    ],
    "license": "MIT",
    "main": "main.js",
    "maintainers": [
        {
            "name": "benjamn"
        }
    ],
    "name": "ast-types",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/benjamn/ast-types.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --full-trace test/run.js"
    },
    "version": "0.9.11",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

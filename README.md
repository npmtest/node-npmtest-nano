# test coverage for  [nano (v6.2.0)](http://github.com/dscape/nano)  [![npm package](https://img.shields.io/npm/v/npmtest-nano.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nano) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nano.svg)](https://travis-ci.org/npmtest/node-npmtest-nano)
#### The official CouchDB client for Node.js

[![NPM](https://nodei.co/npm/nano.png?downloads=true)](https://www.npmjs.com/package/nano)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nano/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nano/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nano/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nano/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nano/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nano/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nano/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nano/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-nano/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-nano/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-nano%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nano/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nano/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-nano%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nano/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nano/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nano/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Apache CouchDB",
        "email": "dev@couchdb.apache.org",
        "url": "http://couchdb.apache.org"
    },
    "bugs": {
        "url": "https://github.com/dscape/nano/issues"
    },
    "dependencies": {
        "debug": "^2.0.0",
        "errs": "^0.3.0",
        "follow": "^0.12.1",
        "request": "^2.53.0",
        "underscore": "^1.7.0"
    },
    "description": "The official CouchDB client for Node.js",
    "devDependencies": {
        "async": "^0.9.0",
        "endswith": "^0.0.0",
        "istanbul": "^0.3.2",
        "jscs": "^1.7.0",
        "jshint": "^2.5.6",
        "nock": "^0.48.1",
        "tape": "^3.0.0",
        "tape-it": "^0.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "314aa08f41e7da388bd2132b9f97ecbc67e057a0",
        "tarball": "https://registry.npmjs.org/nano/-/nano-6.2.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "c03b5528b6b0759f7e001b722199f824163ad3a0",
    "homepage": "http://github.com/dscape/nano",
    "keywords": [
        "couchdb",
        "data",
        "request",
        "json",
        "nosql",
        "micro",
        "nano",
        "database"
    ],
    "license": "Apache-2.0",
    "main": "./lib/nano.js",
    "maintainers": [
        {
            "name": "dscape",
            "email": "nunojobpinto@gmail.com"
        },
        {
            "name": "jhs",
            "email": "jason.h.smith@gmail.com"
        },
        {
            "name": "jo",
            "email": "schmidt@netzmerk.com"
        },
        {
            "name": "pgte",
            "email": "pedro.teixeira@gmail.com"
        }
    ],
    "name": "nano",
    "optionalDependencies": {},
    "pre-commit": [
        "jshint",
        "codestyle",
        "mocked",
        "test",
        "checkcoverage"
    ],
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/dscape/nano.git"
    },
    "scripts": {
        "checkcoverage": "istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "codestyle": "jscs -p google tests/*/*/*.js lib/*.js",
        "coverage": "open coverage/lcov-report/index.html",
        "jshint": "jshint tests/*/*/*.js lib/*.js",
        "mocked": "tape tests/*/*/*.js",
        "test": "DEBUG=* NOCK_OFF=true istanbul cover tape tests/*/*/*.js",
        "unmocked": "NOCK_OFF=true tape tests/*/*/*.js"
    },
    "version": "6.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

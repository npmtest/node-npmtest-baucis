# npmtest-baucis

#### basic test coverage for  [baucis (v1.6.5)](https://github.com/wprl/baucis)  [![npm package](https://img.shields.io/npm/v/npmtest-baucis.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-baucis) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-baucis.svg)](https://travis-ci.org/npmtest/node-npmtest-baucis)

#### Build scalable REST APIs using the open source tools and standards you already know.

[![NPM](https://nodei.co/npm/baucis.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/baucis)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-baucis/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-baucis/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-baucis/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-baucis/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-baucis/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-baucis/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-baucis/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-baucis/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-baucis/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-baucis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-baucis/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-baucis/build/test-report.html](https://npmtest.github.io/node-npmtest-baucis/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-baucis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-baucis/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-baucis/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-baucis/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-baucis/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-baucis/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-baucis/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-baucis/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "William Riley-Land",
        "url": "http://kun.io/wprl"
    },
    "bugs": {
        "url": "https://github.com/wprl/baucis/issues/new"
    },
    "contributors": [
        {
            "name": "eguneys",
            "url": "https://github.com/eguneys"
        },
        {
            "name": "feychenie",
            "url": "https://github.com/feychenie"
        },
        {
            "name": "pirhoo",
            "url": "https://github.com/pirhoo"
        },
        {
            "name": "neverfox",
            "url": "https://github.com/neverfox"
        },
        {
            "name": "lukaszfiszer",
            "url": "https://github.com/lukaszfiszer"
        },
        {
            "name": "lcalvy",
            "url": "https://github.com/lcalvy"
        },
        {
            "name": "stemey",
            "url": "https://github.com/stemey"
        },
        {
            "name": "Illniyar",
            "url": "https://github.com/Illniyar"
        },
        {
            "name": "fanfuzion",
            "url": "https://github.com/fanfuzion"
        },
        {
            "name": "felipefdl",
            "url": "https://github.com/felipefdl"
        },
        {
            "name": "andyzickler",
            "url": "https://github.com/andyzickler"
        }
    ],
    "dependencies": {
        "baucis-json": "^1.0.0",
        "baucis-links": "^1.0.0",
        "deco": "^0.12.0",
        "event-stream": "^3.3.0",
        "rest-error": "^1.2.0",
        "semver": "^4.3.4"
    },
    "description": "Build scalable REST APIs using the open source tools and standards you already know.",
    "devDependencies": {
        "async": "^0.9.0",
        "body-parser": "^1.12.3",
        "expect.js": "^0.3.1",
        "istanbul": "^0.3.13",
        "mocha": "^2.2.4",
        "parse-links": "^0.1.0",
        "passport": "^0.2.0",
        "passport-local": "^1.0.0",
        "request": "^2.55.0",
        "through": "^2.3.7"
    },
    "directories": {},
    "dist": {
        "shasum": "c5e3e2f80bc1d734680e6d0d3aad4870b45904ab",
        "tarball": "https://registry.npmjs.org/baucis/-/baucis-1.6.5.tgz"
    },
    "gitHead": "16d7c1fcb29d4f59b7a1bbc3388ef8450f78598a",
    "homepage": "https://github.com/wprl/baucis",
    "keywords": [
        "REST",
        "RESTful",
        "API",
        "express",
        "mongoose",
        "schema",
        "schemata",
        "model",
        "mde",
        "mongo",
        "rfc2616",
        "web",
        "http"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wprl"
        }
    ],
    "name": "baucis",
    "optionalDependencies": {},
    "peerDependencies": {
        "mongoose": ">=3 <5",
        "express": "^4.12.0"
    },
    "publishConfig": {
        "registry": "http://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wprl/baucis.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha",
        "test": "mocha --bail"
    },
    "version": "1.6.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

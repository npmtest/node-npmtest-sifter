# npmtest-sifter

#### basic test coverage for  [sifter (v0.5.2)](https://github.com/brianreavis/sifter.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sifter.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sifter) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sifter.svg)](https://travis-ci.org/npmtest/node-npmtest-sifter)

#### A library for textually searching arrays and hashes of objects by property (or multiple properties). Designed specifically for autocomplete.

[![NPM](https://nodei.co/npm/sifter.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sifter)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sifter/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sifter/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sifter/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sifter/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sifter/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sifter/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sifter/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sifter/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sifter/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sifter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sifter/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sifter/build/test-report.html](https://npmtest.github.io/node-npmtest-sifter/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sifter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sifter/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sifter/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sifter/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sifter/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sifter/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sifter/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sifter/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Reavis"
    },
    "bin": {
        "sifter": "./bin/sifter.js"
    },
    "bugs": {
        "url": "https://github.com/brianreavis/sifter.js/issues"
    },
    "dependencies": {
        "async": "0.2.x",
        "cardinal": "0.4.x",
        "csv-parse": "^1.1.7",
        "humanize": "0.0.x",
        "microtime": "^2.1.0",
        "optimist": "0.6.x"
    },
    "description": "A library for textually searching arrays and hashes of objects by property (or multiple properties). Designed specifically for autocomplete.",
    "devDependencies": {
        "coveralls": "2.3.x",
        "istanbul": "0.1.x",
        "mocha": "1.12.x",
        "mocha-istanbul": "0.2.x",
        "mocha-lcov-reporter": "0.0.x",
        "uglify-js": "2.4.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4702e3cee3036903da1f194b29e6dc7a4fb59abe",
        "tarball": "https://registry.npmjs.org/sifter/-/sifter-0.5.2.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "4ba7422542bf188c1fdb4bbc341fc4fcc1ff0680",
    "homepage": "https://github.com/brianreavis/sifter.js#readme",
    "keywords": [
        "search",
        "filter",
        "sift",
        "data",
        "results",
        "match",
        "sort",
        "autocomplete"
    ],
    "license": "Apache-2.0",
    "main": "./sifter.js",
    "maintainers": [
        {
            "name": "brianreavis"
        },
        {
            "name": "holic"
        }
    ],
    "name": "sifter",
    "optionalDependencies": {
        "microtime": "^2.1.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/brianreavis/sifter.js.git"
    },
    "scripts": {
        "test": "mocha -R list"
    },
    "version": "0.5.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

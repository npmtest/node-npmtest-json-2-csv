# npmtest-json-2-csv

#### basic test coverage for  [json-2-csv (v2.1.0)](https://github.com/mrodrig/json-2-csv)  [![npm package](https://img.shields.io/npm/v/npmtest-json-2-csv.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-json-2-csv) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-json-2-csv.svg)](https://travis-ci.org/npmtest/node-npmtest-json-2-csv)

#### A JSON to CSV and CSV to JSON converter that natively supports sub-documents and auto-generates the CSV heading.

[![NPM](https://nodei.co/npm/json-2-csv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/json-2-csv)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-json-2-csv/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-2-csv/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-json-2-csv/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-json-2-csv/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-json-2-csv/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-json-2-csv/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-json-2-csv/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-json-2-csv/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-json-2-csv/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-json-2-csv/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-json-2-csv/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-json-2-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-json-2-csv/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-json-2-csv/build/test-report.html](https://npmtest.github.io/node-npmtest-json-2-csv/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-json-2-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-json-2-csv/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-json-2-csv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-json-2-csv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-json-2-csv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-json-2-csv/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-json-2-csv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-json-2-csv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mrodrig"
    },
    "bugs": {
        "url": "https://github.com/mrodrig/json-2-csv/issues"
    },
    "dependencies": {
        "bluebird": "3.4.6",
        "doc-path": "1.0.8",
        "underscore": "1.8.3"
    },
    "description": "A JSON to CSV and CSV to JSON converter that natively supports sub-documents and auto-generates the CSV heading.",
    "devDependencies": {
        "async": "2.0.1",
        "istanbul": "0.4.5",
        "mocha": "3.1.0",
        "should": "11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "00c5505e37524fa57728715ae92f3d23522b2eb1",
        "tarball": "https://registry.npmjs.org/json-2-csv/-/json-2-csv-2.1.0.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "e0da80653bd23342597d905ec1bbb2f8cd13c619",
    "homepage": "https://github.com/mrodrig/json-2-csv",
    "keywords": [
        "json",
        "csv",
        "converter",
        "json2csv",
        "csv2json",
        "json2csv-converter",
        "csv2json-converter",
        "json-2-csv",
        "csv-2-json"
    ],
    "license": "MIT",
    "main": "./lib/converter.js",
    "maintainers": [
        {
            "name": "mrodrig"
        }
    ],
    "name": "json-2-csv",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/mrodrig/json-2-csv.git"
    },
    "scripts": {
        "coverage": "istanbul cover ./node_modules/.bin/_mocha -- -R spec",
        "test": "mocha test/tests.js"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

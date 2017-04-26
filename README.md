# npmtest-sql-template-strings

#### basic test coverage for  [sql-template-strings (v2.2.2)](https://github.com/felixfbecker/node-sql-template-strings#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-sql-template-strings.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sql-template-strings) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sql-template-strings.svg)](https://travis-ci.org/npmtest/node-npmtest-sql-template-strings)

#### ES6 tagged template strings for prepared statements with mysql and postgres

[![NPM](https://nodei.co/npm/sql-template-strings.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sql-template-strings)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sql-template-strings/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sql-template-strings/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sql-template-strings/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sql-template-strings/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sql-template-strings/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sql-template-strings/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sql-template-strings/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sql-template-strings/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sql-template-strings/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sql-template-strings/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sql-template-strings/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sql-template-strings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sql-template-strings/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sql-template-strings/build/test-report.html](https://npmtest.github.io/node-npmtest-sql-template-strings/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sql-template-strings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sql-template-strings/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sql-template-strings/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sql-template-strings/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sql-template-strings/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sql-template-strings/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sql-template-strings/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sql-template-strings/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Becker"
    },
    "bugs": {
        "url": "https://github.com/felixfbecker/node-sql-template-strings/issues"
    },
    "dependencies": {},
    "description": "ES6 tagged template strings for prepared statements with mysql and postgres",
    "devDependencies": {
        "eslint": "^3.4.0",
        "mocha": "^3.0.2",
        "nyc": "^8.1.0",
        "typedoc": "^0.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "3f11508a25addfce217a3042a9d300c3193b96ff",
        "tarball": "https://registry.npmjs.org/sql-template-strings/-/sql-template-strings-2.2.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "84ff820160e6d8b1a06d1e7c408a79b3843e5493",
    "homepage": "https://github.com/felixfbecker/node-sql-template-strings#readme",
    "keywords": [
        "mysql",
        "mysql2",
        "postgres",
        "pg",
        "prepared",
        "statements",
        "placeholder",
        "es6",
        "tagged",
        "template",
        "strings"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "felixfbecker"
        }
    ],
    "name": "sql-template-strings",
    "nyc": {
        "include": [
            "index.js"
        ],
        "exclude": [
            "test/**/*.js"
        ]
    },
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/felixfbecker/node-sql-template-strings.git"
    },
    "scripts": {
        "cover": "nyc --all mocha test",
        "lint": "eslint index.js test",
        "test": "mocha test",
        "typedoc": "typedoc --module es2015 --target es2015 --includeDeclarations --mode file --readme none --out typedoc index.d.ts"
    },
    "typings": "index.d.ts",
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

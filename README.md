# npmtest-orchestrate

test coverage for  [orchestrate (v0.8.2)](http://orchestrate.io/docs)  [![npm package](https://img.shields.io/npm/v/npmtest-orchestrate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-orchestrate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-orchestrate.svg)](https://travis-ci.org/npmtest/node-npmtest-orchestrate)
#### Orchestrate is a database service. It is a simple REST API that is optimized for queries. Orchestrate combines full-text search, graph, time-series, and key/value.

[![NPM](https://nodei.co/npm/orchestrate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/orchestrate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-orchestrate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-orchestrate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-orchestrate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-orchestrate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-orchestrate/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-orchestrate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-orchestrate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-orchestrate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-orchestrate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-orchestrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-orchestrate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-orchestrate/build/test-report.html](https://npmtest.github.io/node-npmtest-orchestrate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-orchestrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-orchestrate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-orchestrate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-orchestrate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-orchestrate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-orchestrate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-orchestrate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-orchestrate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Steve Kaliski",
        "url": "http://stevekaliski.com"
    },
    "bugs": {
        "url": "https://github.com/orchestrate-io/orchestrate.js/issues"
    },
    "dependencies": {
        "kew": "~0.7.0",
        "parse-link-header": "~0.4.1",
        "request": "~2.78.0"
    },
    "description": "Orchestrate is a database service. It is a simple REST API that is optimized for queries. Orchestrate combines full-text search, graph, time-series, and key/value.",
    "devDependencies": {
        "coveralls": "^2.11.4",
        "expect.js": "0.3.1",
        "jscoverage": "^0.6.0",
        "mocha": "^2.3.2",
        "mocha-lcov-reporter": "0.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "8d62cf20f5ad326966efaebb2c888f9fa89469ac",
        "tarball": "https://registry.npmjs.org/orchestrate/-/orchestrate-0.8.2.tgz"
    },
    "gitHead": "e8c81ab099a029508e9da035b4e01db44b519fb2",
    "homepage": "http://orchestrate.io/docs",
    "keywords": [
        "full-text search",
        "search",
        "database",
        "dbaas",
        "graph",
        "orchestrate",
        "key",
        "value",
        "events",
        "time-series"
    ],
    "license": "Apache-2.0",
    "main": "index",
    "maintainers": [
        {
            "name": "benjismith"
        },
        {
            "name": "diegos"
        },
        {
            "name": "dizzyd"
        },
        {
            "name": "dreverri"
        },
        {
            "name": "housejester"
        },
        {
            "name": "j.hita"
        },
        {
            "name": "jorgeelas"
        },
        {
            "name": "sjkaliski"
        }
    ],
    "name": "orchestrate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/orchestrate-io/orchestrate.js.git"
    },
    "scripts": {
        "cov": "jscoverage lib lib-cov",
        "coveralls": "npm run cov && mocha -u tdd -t 5000 -R mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js",
        "report": "npm run cov && mocha -u tdd -R html-cov -t 70000 > coverage.html",
        "test": "npm run cov && mocha -u tdd -t 70000"
    },
    "tags": [
        "orchestrate",
        "driver"
    ],
    "version": "0.8.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

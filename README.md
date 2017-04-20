# npmtest-intern

#### basic test coverage for  [intern (v3.4.3)](http://theintern.io/)  [![npm package](https://img.shields.io/npm/v/npmtest-intern.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-intern) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-intern.svg)](https://travis-ci.org/npmtest/node-npmtest-intern)

#### Intern. A next-generation code testing stack for JavaScript.

[![NPM](https://nodei.co/npm/intern.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/intern)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-intern/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-intern/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-intern/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-intern/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-intern/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-intern/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-intern/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-intern/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-intern/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-intern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-intern/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-intern/build/test-report.html](https://npmtest.github.io/node-npmtest-intern/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-intern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-intern/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-intern/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-intern/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-intern/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-intern/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "intern",
    "version": "3.4.3",
    "main": "./main.js",
    "types": "./typings/intern/intern.d.ts",
    "description": "Intern. A next-generation code testing stack for JavaScript.",
    "repository": {
        "type": "git",
        "url": "https://github.com/theintern/intern.git"
    },
    "license": "BSD-3-Clause",
    "dependencies": {
        "benchmark": "2.1.1",
        "chai": "3.5.0",
        "charm": "0.2.0",
        "diff": "1.1.0",
        "digdug": "~1.6.0",
        "dojo": "2.0.0-alpha.7",
        "glob": "7.0.3",
        "istanbul": "0.4.1",
        "leadfoot": "~1.7.0",
        "lodash-amd": "4.16.4",
        "mimetype": "0.0.8",
        "platform": "1.3.1",
        "source-map": "0.1.33",
        "@types/chai": "3.4.34",
        "@types/node": "6.0.48"
    },
    "devDependencies": {
        "intern": "3.2.3"
    },
    "scripts": {
        "install": "node support/fixdeps.js",
        "update": "node support/fixdeps.js",
        "release": "node support/release.js",
        "test": "node support/test.js"
    },
    "bugs": "https://github.com/theintern/intern/issues",
    "files": [
        "bin",
        "chai.js",
        "client.html",
        "client.js",
        "lib",
        "main.js",
        "order.js",
        "runner.js",
        "support/fixdeps.js",
        "tasks",
        "tests/example.intern.js",
        "typings"
    ],
    "keywords": [
        "javascript",
        "test",
        "unit",
        "testing",
        "ci",
        "continuous integration",
        "bdd",
        "tdd",
        "xunit",
        "istanbul",
        "chai",
        "dojo",
        "toolkit",
        "selenium",
        "sauce labs",
        "code coverage"
    ],
    "homepage": "http://theintern.io/",
    "bin": {
        "intern-client": "./bin/intern-client.js",
        "intern-runner": "./bin/intern-runner.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-performance-now

#### basic test coverage for  [performance-now (v2.1.0)](https://github.com/braveg1rl/performance-now)  [![npm package](https://img.shields.io/npm/v/npmtest-performance-now.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-performance-now) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-performance-now.svg)](https://travis-ci.org/npmtest/node-npmtest-performance-now)

#### Implements performance.now (based on process.hrtime).

[![NPM](https://nodei.co/npm/performance-now.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/performance-now)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-performance-now/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-performance-now/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-performance-now/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-performance-now/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-performance-now/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-performance-now/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-performance-now/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-performance-now/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-performance-now/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-performance-now/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-performance-now/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-performance-now/build/test-report.html](https://npmtest.github.io/node-npmtest-performance-now/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-performance-now/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-performance-now/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-performance-now/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-performance-now/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-performance-now/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-performance-now/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "performance-now",
    "description": "Implements performance.now (based on process.hrtime).",
    "keywords": [],
    "version": "2.1.0",
    "author": "Braveg1rl <braveg1rl@outlook.com>",
    "license": "MIT",
    "homepage": "https://github.com/braveg1rl/performance-now",
    "bugs": "https://github.com/braveg1rl/performance-now/issues",
    "repository": {
        "type": "git",
        "url": "git://github.com/braveg1rl/performance-now.git"
    },
    "private": false,
    "dependencies": {},
    "devDependencies": {
        "bluebird": "^3.4.7",
        "call-delayed": "^1.0.0",
        "chai": "^3.5.0",
        "chai-increasing": "^1.2.0",
        "coffee-script": "~1.12.2",
        "mocha": "~3.2.0",
        "pre-commit": "^1.2.2"
    },
    "optionalDependencies": {},
    "main": "lib/performance-now.js",
    "scripts": {
        "build": "mkdir -p lib && rm -rf lib/* && node_modules/.bin/coffee --compile -m --output lib/ src/",
        "prepublish": "npm test",
        "pretest": "npm run build",
        "test": "node_modules/.bin/mocha",
        "watch": "node_modules/.bin/coffee --watch --compile --output lib/ src/"
    },
    "typings": "src/index.d.ts"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

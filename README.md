# npmtest-is-online

#### basic test coverage for  is-online (v7.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-is-online.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-is-online) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-is-online.svg)](https://travis-ci.org/npmtest/node-npmtest-is-online)

#### Check if the internet connection is up

[![NPM](https://nodei.co/npm/is-online.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/is-online)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-is-online/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-is-online/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-is-online/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-is-online/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-is-online/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-is-online/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-is-online/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-is-online/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-is-online/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-is-online/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-is-online/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-is-online/build/test-report.html](https://npmtest.github.io/node-npmtest-is-online/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-is-online/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-is-online/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-is-online/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-is-online/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-is-online/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-is-online/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-is-online/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-is-online/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "is-online",
    "version": "7.0.0",
    "description": "Check if the internet connection is up",
    "license": "MIT",
    "repository": "sindresorhus/is-online",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "contributors": [
        "silverwind <me@silverwind.io> (github.com/silverwind)"
    ],
    "engines": {
        "node": ">=4"
    },
    "scripts": {
        "test": "xo && ava test.js"
    },
    "files": [
        "index.js",
        "browser.js",
        "hostnames.js"
    ],
    "keywords": [
        "browser",
        "online",
        "offline",
        "is-online",
        "network",
        "connected",
        "connectivity",
        "internet",
        "is",
        "has",
        "detect",
        "hostname",
        "hostnames",
        "dns",
        "socket",
        "reachable",
        "reachability",
        "accessible"
    ],
    "dependencies": {
        "got": "^6.7.1",
        "p-any": "^1.0.0",
        "p-timeout": "^1.0.0",
        "public-ip": "^2.3.0"
    },
    "devDependencies": {
        "ava": "*",
        "xo": "*"
    },
    "browser": "browser.js",
    "xo": {
        "esnext": true
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

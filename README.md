# npmtest-is-online

#### basic test coverage for  [is-online (v7.0.0)](https://github.com/sindresorhus/is-online#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-is-online.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-is-online) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-is-online.svg)](https://travis-ci.org/npmtest/node-npmtest-is-online)

#### Check if the internet connection is up

[![NPM](https://nodei.co/npm/is-online.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/is-online)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-is-online/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-is-online/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-is-online/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-is-online/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-is-online/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-is-online/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-is-online/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-is-online/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-is-online/tree/gh-pages/build)|

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
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "browser": "browser.js",
    "bugs": {
        "url": "https://github.com/sindresorhus/is-online/issues"
    },
    "contributors": [
        {
            "name": "silverwind",
            "url": "github.com/silverwind"
        }
    ],
    "dependencies": {
        "got": "^6.7.1",
        "p-any": "^1.0.0",
        "p-timeout": "^1.0.0",
        "public-ip": "^2.3.0"
    },
    "description": "Check if the internet connection is up",
    "devDependencies": {
        "ava": "*",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "7e2408c0ae1e7e37ba8d50bdb237260d32bfd96e",
        "tarball": "https://registry.npmjs.org/is-online/-/is-online-7.0.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "index.js",
        "browser.js",
        "hostnames.js"
    ],
    "gitHead": "8b092e0d9c6b02b3f743e4c8ba5eca40f0b12396",
    "homepage": "https://github.com/sindresorhus/is-online#readme",
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
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        },
        {
            "name": "silverwind"
        }
    ],
    "name": "is-online",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/is-online.git"
    },
    "scripts": {
        "test": "xo && ava test.js"
    },
    "version": "7.0.0",
    "xo": {
        "esnext": true
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-mitm

#### basic test coverage for  [mitm (v1.3.2)](https://github.com/moll/node-mitm)  [![npm package](https://img.shields.io/npm/v/npmtest-mitm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mitm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mitm.svg)](https://travis-ci.org/npmtest/node-npmtest-mitm)

#### Intercept and mock outgoing network TCP connections and HTTP requests for testing. Intercepts and gives you a Net.Socket, Http.IncomingMessage and Http.ServerResponse to test and respond with. Useful when testing code that hits remote servers.

[![NPM](https://nodei.co/npm/mitm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mitm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mitm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mitm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mitm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mitm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mitm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mitm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mitm/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mitm/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mitm/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mitm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mitm/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mitm/build/test-report.html](https://npmtest.github.io/node-npmtest-mitm/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mitm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mitm/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mitm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mitm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mitm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mitm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mitm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mitm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andri Möll",
        "url": "http://themoll.com"
    },
    "bugs": {
        "url": "https://github.com/moll/node-mitm/issues"
    },
    "dependencies": {
        "underscore": ">= 1.1.6 < 1.6"
    },
    "description": "Intercept and mock outgoing network TCP connections and HTTP requests for testing. Intercepts and gives you a Net.Socket, Http.IncomingMessage and Http.ServerResponse to test and respond with. Useful when testing code that hits remote servers.",
    "devDependencies": {
        "mocha": ">= 1.12.0 < 1.19",
        "must": ">= 0.13 < 0.14",
        "semver": ">= 5 < 6",
        "sinon": ">= 1.9 < 2"
    },
    "directories": {},
    "dist": {
        "shasum": "188d8620601a1569133d9e7085fcf011e799265d",
        "tarball": "https://registry.npmjs.org/mitm/-/mitm-1.3.2.tgz"
    },
    "engines": {
        "node": ">= 0.10.24"
    },
    "gitHead": "a31ebbfb26855381e91c91f3da50a876b919c587",
    "homepage": "https://github.com/moll/node-mitm",
    "keywords": [
        "http",
        "https",
        "intercept",
        "interception",
        "mock",
        "network",
        "socket",
        "tcp",
        "test",
        "webmock"
    ],
    "licenses": [
        {
            "type": "LAGPL",
            "url": "https://github.com/moll/node-mitm/blob/master/LICENSE"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "moll"
        }
    ],
    "name": "mitm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/moll/node-mitm.git"
    },
    "scripts": {},
    "version": "1.3.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-agentkeepalive

#### basic test coverage for  agentkeepalive (v3.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-agentkeepalive.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-agentkeepalive) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-agentkeepalive.svg)](https://travis-ci.org/npmtest/node-npmtest-agentkeepalive)

#### Missing keepalive http.Agent

[![NPM](https://nodei.co/npm/agentkeepalive.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/agentkeepalive)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-agentkeepalive/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-agentkeepalive/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-agentkeepalive/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-agentkeepalive/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-agentkeepalive/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-agentkeepalive/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-agentkeepalive/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-agentkeepalive/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-agentkeepalive/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-agentkeepalive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-agentkeepalive/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-agentkeepalive/build/test-report.html](https://npmtest.github.io/node-npmtest-agentkeepalive/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-agentkeepalive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-agentkeepalive/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-agentkeepalive/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-agentkeepalive/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-agentkeepalive/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-agentkeepalive/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-agentkeepalive/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-agentkeepalive/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "agentkeepalive",
    "version": "3.1.0",
    "description": "Missing keepalive http.Agent",
    "main": "index.js",
    "browser": "browser.js",
    "files": [
        "index.js",
        "browser.js",
        "lib"
    ],
    "scripts": {
        "test": "egg-bin test",
        "cov": "egg-bin cov",
        "ci": "npm run lint && npm run cov",
        "lint": "eslint lib test index.js"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/node-modules/agentkeepalive.git"
    },
    "bugs": {
        "url": "https://github.com/node-modules/agentkeepalive/issues"
    },
    "keywords": [
        "http",
        "https",
        "agent",
        "keepalive",
        "agentkeepalive"
    ],
    "dependencies": {
        "humanize-ms": "^1.2.0"
    },
    "devDependencies": {
        "egg-bin": "^1.9.1",
        "egg-ci": "^1.1.0",
        "eslint": "^3.12.2",
        "eslint-config-egg": "^3.2.0",
        "pedding": "1"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "ci": {
        "version": "4.3.2, 4, 6, 7"
    },
    "author": "fengmk2 <fengmk2@gmail.com> (https://fengmk2.com)",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

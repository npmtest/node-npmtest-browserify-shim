# npmtest-browserify-shim

#### test coverage for  [browserify-shim (v3.8.14)](https://github.com/thlorenz/browserify-shim#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-browserify-shim.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-browserify-shim) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-browserify-shim.svg)](https://travis-ci.org/npmtest/node-npmtest-browserify-shim)

#### Makes CommonJS-incompatible modules browserifyable.

[![NPM](https://nodei.co/npm/browserify-shim.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browserify-shim)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-browserify-shim/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-shim/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-shim/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-browserify-shim/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-browserify-shim/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-browserify-shim/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-browserify-shim/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-browserify-shim/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-browserify-shim/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-browserify-shim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-browserify-shim/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-browserify-shim/build/test-report.html](https://npmtest.github.io/node-npmtest-browserify-shim/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-browserify-shim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-browserify-shim/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-browserify-shim/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browserify-shim/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browserify-shim/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browserify-shim/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-browserify-shim/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-browserify-shim/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Thorsten Lorenz",
        "url": "thlorenz.com"
    },
    "bugs": {
        "url": "https://github.com/thlorenz/browserify-shim/issues"
    },
    "dependencies": {
        "exposify": "~0.5.0",
        "mothership": "~0.2.0",
        "rename-function-calls": "~0.1.0",
        "resolve": "~0.6.1",
        "through": "~2.3.4"
    },
    "description": "Makes CommonJS-incompatible modules browserifyable.",
    "devDependencies": {
        "browserify": ">= 13",
        "jsdom": "^5.4.2",
        "ncp": "~0.5.0",
        "proxyquire": "~0.5.1",
        "request": "~2.12.0",
        "rimraf": "~2.2.6",
        "tap": "^1.1.0",
        "test-peer-range": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "bf1057026932d3253c75ef7dd714f3b877edec6b",
        "tarball": "https://registry.npmjs.org/browserify-shim/-/browserify-shim-3.8.14.tgz"
    },
    "gitHead": "8bb2a4fc3313dce4149d65e6340fbfc101f00bc3",
    "homepage": "https://github.com/thlorenz/browserify-shim#readme",
    "keywords": [
        "browserify",
        "browserify-transform",
        "shim",
        "global",
        "globals",
        "transform",
        "window",
        "commonjs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "thlorenz"
        },
        {
            "name": "bendrucker"
        }
    ],
    "name": "browserify-shim",
    "optionalDependencies": {},
    "peerDependencies": {
        "browserify": ">= 2.3"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/thlorenz/browserify-shim.git"
    },
    "scripts": {
        "dependency-with-global": "npm install opener && cd ./examples/dependency-with-global && npm install && node build.js && opener index.html",
        "dependency-with-global-diag": "npm install opener && cd ./examples/dependency-with-global && npm install && node build-diag.js && opener index.html",
        "expose-jquery": "npm install opener && cd ./examples/expose-jquery && npm install && node build.js && opener index.html",
        "expose-jquery-diag": "npm install opener && cd ./examples/expose-jquery && npm install && node build-diag.js && opener index.html",
        "shim-jquery": "npm install opener && cd ./examples/shim-jquery && npm install && node build.js && opener index.html",
        "shim-jquery-diag": "npm install opener && cd ./examples/shim-jquery && npm install && node build-diag.js && opener index.html",
        "test": "test-peer-range browserify",
        "test-main": "tap test/*.js && tap test/shim/*.js"
    },
    "version": "3.8.14"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

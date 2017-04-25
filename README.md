# npmtest-lru-cache

#### basic test coverage for  [lru-cache (v4.0.2)](https://github.com/isaacs/node-lru-cache#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-lru-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lru-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lru-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-lru-cache)

#### A cache object that deletes the least-recently-used items.

[![NPM](https://nodei.co/npm/lru-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lru-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lru-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lru-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lru-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lru-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lru-cache/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-lru-cache/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-lru-cache/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lru-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lru-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lru-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lru-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lru-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lru-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lru-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-lru-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lru-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lru-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lru-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lru-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lru-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lru-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lru-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lru-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Isaac Z. Schlueter"
    },
    "bugs": {
        "url": "https://github.com/isaacs/node-lru-cache/issues"
    },
    "dependencies": {
        "pseudomap": "^1.0.1",
        "yallist": "^2.0.0"
    },
    "description": "A cache object that deletes the least-recently-used items.",
    "devDependencies": {
        "standard": "^5.4.1",
        "tap": "^8.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "1d17679c069cda5d040991a09dbc2c0db377e55e",
        "tarball": "https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.2.tgz"
    },
    "files": [
        "lib/lru-cache.js"
    ],
    "gitHead": "f25bdae0b4bb0166a75fa01d664a3e3cece1ce98",
    "homepage": "https://github.com/isaacs/node-lru-cache#readme",
    "keywords": [
        "mru",
        "lru",
        "cache"
    ],
    "license": "ISC",
    "main": "lib/lru-cache.js",
    "maintainers": [
        {
            "name": "isaacs"
        },
        {
            "name": "othiym23"
        }
    ],
    "name": "lru-cache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/isaacs/node-lru-cache.git"
    },
    "scripts": {
        "posttest": "standard test/*.js lib/*.js",
        "test": "tap test --100"
    },
    "version": "4.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-koa-static-cache

#### basic test coverage for  [koa-static-cache (v5.0.1)](https://github.com/koajs/static-cache#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-static-cache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-static-cache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-static-cache.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-static-cache)

#### Static cache for koa

[![NPM](https://nodei.co/npm/koa-static-cache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-static-cache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-static-cache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-static-cache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-static-cache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-static-cache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-static-cache/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-koa-static-cache/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-koa-static-cache/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-static-cache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-static-cache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-static-cache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-static-cache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-static-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-static-cache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-static-cache/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-static-cache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-static-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-static-cache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-static-cache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-static-cache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-static-cache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-static-cache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-static-cache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-static-cache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/koajs/static-cache/issues"
    },
    "contributors": [
        {
            "name": "Jeremiah Senkpiel",
            "url": "https://searchbeam.jit.su"
        },
        {
            "name": "dead_horse",
            "url": "http://deadhorse.me"
        }
    ],
    "dependencies": {
        "compressible": "~2.0.6",
        "debug": "*",
        "fs-readdir-recursive": "~1.0.0",
        "mime-types": "~2.1.8",
        "mz": "~2.4.0"
    },
    "description": "Static cache for koa",
    "devDependencies": {
        "bluebird": "3",
        "istanbul": "~0.4.1",
        "koa": "2",
        "mocha": "2",
        "should": "8",
        "should-http": "0.0.4",
        "supertest": "1"
    },
    "directories": {},
    "dist": {
        "shasum": "3d3ef5b857ac8391c0f1cd294f4a91c6082615ab",
        "tarball": "https://registry.npmjs.org/koa-static-cache/-/koa-static-cache-5.0.1.tgz"
    },
    "engines": {
        "node": ">= 7.6.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "73ca4dad97a403af502eb57bd61f86e7f178320c",
    "homepage": "https://github.com/koajs/static-cache#readme",
    "keywords": [
        "koa",
        "middleware",
        "file",
        "static",
        "cache",
        "gzip",
        "sendfile"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "jongleberry"
        },
        {
            "name": "tjholowaychuk"
        },
        {
            "name": "dead-horse"
        },
        {
            "name": "dead_horse"
        },
        {
            "name": "juliangruber"
        },
        {
            "name": "fengmk2"
        },
        {
            "name": "eivifj"
        },
        {
            "name": "aheckmann"
        },
        {
            "name": "coderhaoxin"
        }
    ],
    "name": "koa-static-cache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/koajs/static-cache.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "5.0.1",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">= 7.6.0"
            },
            "pkgid": "koa-static-cache@5.0.1"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": ">= 7.6.0"
            },
            "pkgid": "koa-static-cache@5.0.1"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

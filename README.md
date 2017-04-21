# npmdoc-fastparallel

#### api documentation for  [fastparallel (v2.3.0)](https://github.com/mcollina/fastparallel)  [![npm package](https://img.shields.io/npm/v/npmdoc-fastparallel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-fastparallel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-fastparallel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-fastparallel)

#### Zero-overhead asynchronous parallel/each/map function call

[![NPM](https://nodei.co/npm/fastparallel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fastparallel)

- [https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fastparallel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fastparallel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-fastparallel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-fastparallel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fastparallel",
    "version": "2.3.0",
    "description": "Zero-overhead asynchronous parallel/each/map function call",
    "main": "parallel.js",
    "scripts": {
        "lint": "standard",
        "test": "tape test.js | faucet"
    },
    "pre-commit": [
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/mcollina/fastparallel.git"
    },
    "keywords": [
        "parallel",
        "fast",
        "async"
    ],
    "author": "Matteo Collina <hello@matteocollina.com>",
    "license": "ISC",
    "bugs": {
        "url": "https://github.com/mcollina/fastparallel/issues"
    },
    "homepage": "https://github.com/mcollina/fastparallel",
    "devDependencies": {
        "async": "^2.0.0-rc.5",
        "fastbench": "^1.0.1",
        "faucet": "0.0.1",
        "insync": "^2.1.0",
        "items": "^2.1.0",
        "neo-async": "^1.8.2",
        "parallelize": "^3.0.0",
        "pre-commit": "^1.1.3",
        "standard": "^7.1.0",
        "tape": "^4.5.0"
    },
    "dependencies": {
        "reusify": "^1.0.0",
        "xtend": "^4.0.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

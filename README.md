# npmdoc-hyperlog

#### api documentation for  [hyperlog (v4.12.1)](https://github.com/mafintosh/hyperlog)  [![npm package](https://img.shields.io/npm/v/npmdoc-hyperlog.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hyperlog) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hyperlog.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hyperlog)

#### Merkle DAG that replicates based on scuttlebutt logs and causal linking

[![NPM](https://nodei.co/npm/hyperlog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hyperlog)

- [https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hyperlog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hyperlog/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hyperlog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hyperlog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus",
        "url": "@mafintosh"
    },
    "browserify": {
        "transform": [
            "brfs"
        ]
    },
    "bugs": {
        "url": "https://github.com/mafintosh/hyperlog/issues"
    },
    "dependencies": {
        "after-all": "^2.0.2",
        "bitfield": "^1.1.2",
        "brfs": "^1.4.0",
        "cuid": "^1.2.5",
        "debug": "^2.2.0",
        "defined": "^1.0.0",
        "duplexify": "^3.4.2",
        "framed-hash": "^1.1.0",
        "from2": "^2.1.0",
        "length-prefixed-stream": "^1.3.0",
        "level-enumerate": "^1.0.1",
        "level-logs": "^1.1.0",
        "lexicographic-integer": "^1.1.0",
        "mutexify": "^1.1.0",
        "protocol-buffers": "^3.1.2",
        "pump": "^1.0.0",
        "run-parallel": "^1.1.6",
        "run-waterfall": "^1.1.3",
        "stream-collector": "^1.0.1",
        "through2": "^2.0.0"
    },
    "description": "Merkle DAG that replicates based on scuttlebutt logs and causal linking",
    "devDependencies": {
        "bs58": "^3.0.0",
        "memdb": "^1.0.1",
        "multihashing": "^0.2.0",
        "standard": "^5.0.0",
        "tape": "^4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6c7cdc2626f73441f2d93b9d6f45838fd17d9b5d",
        "tarball": "https://registry.npmjs.org/hyperlog/-/hyperlog-4.12.1.tgz"
    },
    "gitHead": "df15dc61e913f5db6cf7a31c1c1d0da1d1580be9",
    "homepage": "https://github.com/mafintosh/hyperlog",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "substack"
        }
    ],
    "name": "hyperlog",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/hyperlog.git"
    },
    "scripts": {
        "test": "standard && tape test/*"
    },
    "version": "4.12.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

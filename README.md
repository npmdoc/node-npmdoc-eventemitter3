# npmdoc-eventemitter3

#### basic api documentation for  [eventemitter3 (v2.0.3)](https://github.com/primus/eventemitter3#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventemitter3.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventemitter3) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventemitter3.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventemitter3)

#### EventEmitter3 focuses on performance while maintaining a Node.js AND browser compatible interface.

[![NPM](https://nodei.co/npm/eventemitter3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventemitter3)

- [https://npmdoc.github.io/node-npmdoc-eventemitter3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/primus/eventemitter3/issues"
    },
    "dependencies": {},
    "description": "EventEmitter3 focuses on performance while maintaining a Node.js AND browser compatible interface.",
    "devDependencies": {
        "assume": "~1.4.1",
        "browserify": "~14.1.0",
        "mocha": "~3.2.0",
        "nyc": "~10.2.0",
        "pre-commit": "~1.2.0",
        "uglify-js": "~2.8.20",
        "zuul": "~3.11.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b5e1079b59fb5e1ba2771c0a993be060a58c99ba",
        "tarball": "https://registry.npmjs.org/eventemitter3/-/eventemitter3-2.0.3.tgz"
    },
    "gitHead": "9afe1b539e52ec4b8eb4e07d69a5deb5f25c326b",
    "homepage": "https://github.com/primus/eventemitter3#readme",
    "keywords": [
        "EventEmitter",
        "EventEmitter2",
        "EventEmitter3",
        "Events",
        "addEventListener",
        "addListener",
        "emit",
        "emits",
        "emitter",
        "event",
        "once",
        "pub/sub",
        "publish",
        "reactor",
        "subscribe"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "v1"
        },
        {
            "name": "3rdeden"
        },
        {
            "name": "lpinca"
        }
    ],
    "name": "eventemitter3",
    "optionalDependencies": {},
    "pre-commit": "sync, test",
    "repository": {
        "type": "git",
        "url": "git://github.com/primus/eventemitter3.git"
    },
    "scripts": {
        "benchmark": "find benchmarks/run -name '*.js' -exec benchmarks/start.sh {} \\;",
        "build": "mkdir -p umd && browserify index.js -s EventEmitter3 | uglifyjs -m -o umd/eventemitter3.min.js",
        "prepublish": "npm run build",
        "sync": "node versions.js",
        "test": "nyc --reporter=html --reporter=text mocha",
        "test-browser": "zuul -- test.js"
    },
    "typings": "index.d.ts",
    "version": "2.0.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

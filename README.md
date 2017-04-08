# api documentation for  [eventemitter3 (v2.0.3)](https://github.com/primus/eventemitter3#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eventemitter3.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eventemitter3) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eventemitter3.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eventemitter3)
#### EventEmitter3 focuses on performance while maintaining a Node.js AND browser compatible interface.

[![NPM](https://nodei.co/npm/eventemitter3.png?downloads=true)](https://www.npmjs.com/package/eventemitter3)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-eventemitter3%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventemitter3/build/apidoc.html)

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
            "name": "v1",
            "email": "npm@3rd-Eden.com"
        },
        {
            "name": "3rdeden",
            "email": "npm@3rd-Eden.com"
        },
        {
            "name": "lpinca",
            "email": "luigipinca@gmail.com"
        }
    ],
    "name": "eventemitter3",
    "optionalDependencies": {},
    "pre-commit": "sync, test",
    "readme": "ERROR: No README data found!",
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
    "version": "2.0.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eventemitter3](#apidoc.module.eventemitter3)
1.  boolean <span class="apidocSignatureSpan">eventemitter3.</span>prefixed
1.  [function <span class="apidocSignatureSpan">eventemitter3.</span>EventEmitter ()](#apidoc.element.eventemitter3.EventEmitter)



# <a name="apidoc.module.eventemitter3"></a>[module eventemitter3](#apidoc.module.eventemitter3)

#### <a name="apidoc.element.eventemitter3.EventEmitter"></a>[function <span class="apidocSignatureSpan">eventemitter3.</span>EventEmitter ()](#apidoc.element.eventemitter3.EventEmitter)
- description and source-code
```javascript
function EventEmitter() {
  this._events = new Events();
  this._eventsCount = 0;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

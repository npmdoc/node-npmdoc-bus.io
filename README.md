# npmdoc-bus.io

#### basic api documentation for  [bus.io (v0.7.3)](https://github.com/turbonetix/bus.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-bus.io.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-bus.io) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-bus.io.svg)](https://travis-ci.org/npmdoc/node-npmdoc-bus.io)

#### An express inspired, event-driven framework for building real time distributed applications over socket.io and redis.

[![NPM](https://nodei.co/npm/bus.io.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bus.io)

- [https://npmdoc.github.io/node-npmdoc-bus.io/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bus.io/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bus.io/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bus.io/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-bus.io/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-bus.io/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bus.io",
    "version": "0.7.3",
    "description": "An express inspired, event-driven framework for building real time distributed applications over socket.io and redis.",
    "main": "index.js",
    "scripts": {
        "test": "grunt"
    },
    "repository": {
        "type": "git",
        "url": "git@github.com:turbonetix/bus.io.git"
    },
    "keywords": [
        "bus",
        "io",
        "socket.io",
        "kue",
        "redis",
        "message",
        "event",
        "driven",
        "publish",
        "subscribe",
        "producer",
        "consumer",
        "sender",
        "receiver",
        "queue",
        "exchange",
        "network",
        "socket",
        "distributed",
        "service",
        "websockets"
    ],
    "author": "Nathan G. Romano <nathan.g.romano@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/turbonetix/bus.io/issues"
    },
    "homepage": "https://github.com/turbonetix/bus.io",
    "dependencies": {
        "bus.io-client": "^0.2",
        "bus.io-common": "^0.2",
        "bus.io-exchange": "^0.5.3",
        "bus.io-messages": "^0.2",
        "bus.io-receiver": "^0.1.5",
        "debug": "~2",
        "socket.io": "^1.0.2"
    },
    "devDependencies": {
        "socket.io": "^1.0.2",
        "socket.io-client": "~1.0.2",
        "coffee-script": "^1.7.1",
        "grunt-cli": "^0.1.13",
        "grunt": "^0.4.5",
        "grunt-jasmine-bundle": "~0.2.0",
        "sandboxed-module": "~0.3.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

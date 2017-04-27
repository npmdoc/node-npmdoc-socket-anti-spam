# npmdoc-socket-anti-spam

#### basic api documentation for  [socket-anti-spam (v1.1.8)](https://github.com/michaeldegroot/socket-anti-spam#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-socket-anti-spam.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-socket-anti-spam) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-socket-anti-spam.svg)](https://travis-ci.org/npmdoc/node-npmdoc-socket-anti-spam)

#### This module prevents socket.emit spams by clients via ip bans

[![NPM](https://nodei.co/npm/socket-anti-spam.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/socket-anti-spam)

- [https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-socket-anti-spam/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "michaeldegroot"
    },
    "bugs": {
        "url": "https://github.com/michaeldegroot/socket-anti-spam/issues"
    },
    "dependencies": {
        "moment": "^2.12.0"
    },
    "description": "This module prevents socket.emit spams by clients via ip bans",
    "devDependencies": {
        "assert": "^1.3.0",
        "assert-plus": "^1.0.0",
        "coveralls": "^2.11.4",
        "express": "^4.13.3",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2",
        "mocha-lcov-reporter": "^1.2.0",
        "node-static": "^0.7.8",
        "request": "^2.67.0",
        "socket.io": "^1.5.0",
        "socket.io-client": "^1.3.7"
    },
    "directories": {},
    "dist": {
        "shasum": "0ba0a501aee6eb1ef64ddd72c14b99c1ba78b6dc",
        "tarball": "https://registry.npmjs.org/socket-anti-spam/-/socket-anti-spam-1.1.8.tgz"
    },
    "gitHead": "630586ffc8c7220e1949441d2db9922c55ae3176",
    "homepage": "https://github.com/michaeldegroot/socket-anti-spam#readme",
    "keywords": [
        "socket.io",
        "antispam",
        "anti",
        "spam",
        "socket"
    ],
    "license": "MIT",
    "main": "antispam.js",
    "maintainers": [
        {
            "name": "michaeldegroot"
        }
    ],
    "name": "socket-anti-spam",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/michaeldegroot/socket-anti-spam.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/*",
        "coveralls": "npm bin /istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec ./test/* && node node_modules/coveralls/bin/coveralls.js < coverage/lcov.info",
        "test": "mocha"
    },
    "version": "1.1.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

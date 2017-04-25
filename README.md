# npmtest-ws

#### basic test coverage for  [ws (v2.3.1)](https://github.com/websockets/ws)  [![npm package](https://img.shields.io/npm/v/npmtest-ws.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ws) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ws.svg)](https://travis-ci.org/npmtest/node-npmtest-ws)

#### Simple to use, blazing fast and thoroughly tested websocket client and server for Node.js

[![NPM](https://nodei.co/npm/ws.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ws)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ws/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ws/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ws/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ws/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ws/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ws/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ws/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ws/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ws/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ws/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ws/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ws/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ws/build/test-report.html](https://npmtest.github.io/node-npmtest-ws/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ws/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ws/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ws/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ws/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ws/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ws/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Einar Otto Stangvik",
        "url": "http://2x.io"
    },
    "bugs": {
        "url": "https://github.com/websockets/ws/issues"
    },
    "dependencies": {
        "safe-buffer": "~5.0.1",
        "ultron": "~1.1.0"
    },
    "description": "Simple to use, blazing fast and thoroughly tested websocket client and server for Node.js",
    "devDependencies": {
        "benchmark": "~2.1.2",
        "bufferutil": "~3.0.0",
        "eslint": "~3.19.0",
        "eslint-config-standard": "~10.2.0",
        "eslint-plugin-import": "~2.2.0",
        "eslint-plugin-node": "~4.2.0",
        "eslint-plugin-promise": "~3.5.0",
        "eslint-plugin-standard": "~3.0.0",
        "mocha": "~3.2.0",
        "nyc": "~10.2.0",
        "utf-8-validate": "~3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6b94b3e447cb6a363f785eaf94af6359e8e81c80",
        "tarball": "https://registry.npmjs.org/ws/-/ws-2.3.1.tgz"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "732aaf06b76700f104eeff2740e1896be4e88199",
    "homepage": "https://github.com/websockets/ws",
    "keywords": [
        "HyBi",
        "Push",
        "RFC-6455",
        "WebSocket",
        "WebSockets",
        "real-time"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "3rdeden"
        },
        {
            "name": "einaros"
        },
        {
            "name": "lpinca"
        },
        {
            "name": "v1"
        }
    ],
    "name": "ws",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/websockets/ws.git"
    },
    "scripts": {
        "integration": "eslint . && mocha test/*.integration.js",
        "lint": "eslint .",
        "test": "eslint . && nyc --reporter=html --reporter=text mocha test/*.test.js"
    },
    "version": "2.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

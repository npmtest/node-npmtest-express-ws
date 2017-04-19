# npmtest-express-ws

#### test coverage for  [express-ws (v3.0.0)](https://github.com/HenningM/express-ws)  [![npm package](https://img.shields.io/npm/v/npmtest-express-ws.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-ws) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-ws.svg)](https://travis-ci.org/npmtest/node-npmtest-express-ws)

#### WebSocket endpoints for Express applications

[![NPM](https://nodei.co/npm/express-ws.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-ws)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-ws/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-ws/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-ws/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-ws/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-ws/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-ws/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-ws/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-ws/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-ws/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-ws/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-ws/build/test-report.html](https://npmtest.github.io/node-npmtest-express-ws/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-ws/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-ws/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-ws/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-ws/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-ws/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-ws/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-ws/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henning Morud"
    },
    "bugs": {
        "url": "https://github.com/HenningM/express-ws/issues"
    },
    "contributors": [
        {
            "name": "Jesús Leganés Combarro"
        },
        {
            "name": "Sven Slootweg"
        },
        {
            "name": "Andrew Phillips"
        },
        {
            "name": "Nicholas Schell"
        },
        {
            "name": "Max Truxa"
        },
        {
            "name": "Kræn Hansen"
        }
    ],
    "dependencies": {
        "ws": "^2.0.0"
    },
    "description": "WebSocket endpoints for Express applications",
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-preset-es2015": "^6.5.0",
        "eslint": "^3.15.0",
        "eslint-config-airbnb": "^14.1.0",
        "eslint-plugin-import": "^2.2.0",
        "express": "^5.0.0-alpha.1"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "7ddaaf3b7c758865c099905989911b6234477dbd",
        "tarball": "https://registry.npmjs.org/express-ws/-/express-ws-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4.5.0"
    },
    "gitHead": "7afeb2f04f94d6400fa1f99e1c097b796ff9d410",
    "homepage": "https://github.com/HenningM/express-ws",
    "keywords": [
        "express",
        "ws",
        "websocket"
    ],
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "henningm"
        }
    ],
    "name": "express-ws",
    "optionalDependencies": {},
    "peerDependencies": {
        "express": "^4.0.0 || ^5.0.0-alpha.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/HenningM/express-ws.git"
    },
    "scripts": {
        "build": "babel src/ -d lib/",
        "lint": "eslint src/",
        "prepublish": "npm run build"
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

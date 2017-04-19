# npmtest-qrcode

#### test coverage for  [qrcode (v0.8.1)](http://github.com/soldair/node-qrcode)  [![npm package](https://img.shields.io/npm/v/npmtest-qrcode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-qrcode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-qrcode.svg)](https://travis-ci.org/npmtest/node-npmtest-qrcode)

#### QRCode / 2d Barcode api with both server side and client side support using canvas

[![NPM](https://nodei.co/npm/qrcode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qrcode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-qrcode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-qrcode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-qrcode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-qrcode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-qrcode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-qrcode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-qrcode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-qrcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-qrcode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-qrcode/build/test-report.html](https://npmtest.github.io/node-npmtest-qrcode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-qrcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-qrcode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qrcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-qrcode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-qrcode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan Day"
    },
    "bin": {
        "qrcode": "./bin/qrcode"
    },
    "browser": {
        "./lib/index.js": "./lib/browser.js",
        "./lib/utils/buffer.js": "./lib/utils/typedarray-buffer.js"
    },
    "bugs": {
        "url": "https://github.com/soldair/node-qrcode/issues"
    },
    "contributors": [
        {
            "name": "Vincenzo Greco"
        }
    ],
    "dependencies": {
        "colors": "*",
        "dijkstrajs": "^1.0.1",
        "isarray": "^2.0.1",
        "pngjs": "^2.3.1"
    },
    "description": "QRCode / 2d Barcode api with both server side and client side support using canvas",
    "devDependencies": {
        "browserify": "^14.1.0",
        "canvas": "^1.6.4",
        "canvasutil": "*",
        "express": "2.5.x",
        "libxmljs": "^0.18.0",
        "os-tmpdir": "^1.0.2",
        "sinon": "^1.17.7",
        "standard": "*",
        "tap": "*",
        "uglify-js": "^2.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5e802442cabdcacd4175b13b9546c063e1a99a92",
        "tarball": "https://registry.npmjs.org/qrcode/-/qrcode-0.8.1.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "bin",
        "build",
        "lib",
        "helper"
    ],
    "gitHead": "61e24e7daec1b6eb48397cc4102dbd8d8c9f0b1c",
    "homepage": "http://github.com/soldair/node-qrcode",
    "keywords": [
        "canvas",
        "qrcode",
        "barcode"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "soldair"
        },
        {
            "name": "vigreco"
        }
    ],
    "name": "qrcode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/soldair/node-qrcode.git"
    },
    "scripts": {
        "build": "node build.js",
        "lint": "standard",
        "prepublish": "npm run build",
        "pretest": "npm run lint",
        "test": "node test.js"
    },
    "standard": {
        "ignore": [
            "build/",
            "examples/vendors/"
        ]
    },
    "version": "0.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

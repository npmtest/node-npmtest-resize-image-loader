# npmtest-resize-image-loader

#### basic test coverage for  resize-image-loader (v1.0.2)  [![npm package](https://img.shields.io/npm/v/npmtest-resize-image-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-resize-image-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-resize-image-loader.svg)](https://travis-ci.org/npmtest/node-npmtest-resize-image-loader)

#### Responsive image loader for webpack

[![NPM](https://nodei.co/npm/resize-image-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/resize-image-loader)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-resize-image-loader/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-resize-image-loader/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-resize-image-loader/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-resize-image-loader/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-resize-image-loader/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-resize-image-loader/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-resize-image-loader/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-resize-image-loader/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-resize-image-loader/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-resize-image-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-resize-image-loader/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-resize-image-loader/build/test-report.html](https://npmtest.github.io/node-npmtest-resize-image-loader/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-resize-image-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-resize-image-loader/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-resize-image-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-resize-image-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-resize-image-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-resize-image-loader/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-resize-image-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-resize-image-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "resize-image-loader",
    "version": "1.0.2",
    "description": "Responsive image loader for webpack",
    "author": "Puppybits @puppybits",
    "keywords": "webpack image resize responsive adaptive",
    "scripts": {
        "test": "DEBUG=resize-image-loader webpack --config test/webpack.config.js"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git@github.com:puppybits/resize-image-loader.git"
    },
    "dependencies": {
        "datauri": "^1.0.4",
        "debug": "^2.2.0",
        "file-loader": "^0.9.0",
        "loader-utils": "^0.2.16",
        "lwip": "0.0.9"
    },
    "peerDependencies": {
        "gm": "*",
        "file-loader": "*"
    },
    "devDependencies": {
        "webpack": "^1.13.1"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

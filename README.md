# npmtest-fuse.js

#### basic test coverage for  [fuse.js (v2.7.3)](http://fusejs.io)  [![npm package](https://img.shields.io/npm/v/npmtest-fuse.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fuse.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fuse.js.svg)](https://travis-ci.org/npmtest/node-npmtest-fuse.js)

#### Lightweight fuzzy-search

[![NPM](https://nodei.co/npm/fuse.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fuse.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fuse.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fuse.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fuse.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fuse.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fuse.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-fuse.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-fuse.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fuse.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fuse.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fuse.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fuse.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fuse.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fuse.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fuse.js/build/test-report.html](https://npmtest.github.io/node-npmtest-fuse.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fuse.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fuse.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fuse.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fuse.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fuse.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fuse.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fuse.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fuse.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kirollos Risk",
        "url": "http://kiro.me"
    },
    "bugs": {
        "url": "https://github.com/krisk/Fuse/issues"
    },
    "dependencies": {},
    "description": "Lightweight fuzzy-search",
    "devDependencies": {
        "babel-core": "^6.24.1",
        "babel-loader": "^6.4.1",
        "babel-plugin-add-module-exports": "0.2.1",
        "babel-preset-es2015": "^6.24.1",
        "babel-preset-stage-2": "^6.24.1",
        "vows": "0.5.x",
        "webpack": "^2.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "dd9c7ac3e59420ab057e2b25f4e3bddae4f940a5",
        "tarball": "https://registry.npmjs.org/fuse.js/-/fuse.js-2.7.3.tgz"
    },
    "gitHead": "194692ae70c41f5dbd3805d4048e1ac3b776acb6",
    "homepage": "http://fusejs.io",
    "keywords": [
        "fuzzy",
        "bitap"
    ],
    "license": "Apache",
    "main": "dist/fuse.js",
    "maintainers": [
        {
            "name": "krisk"
        }
    ],
    "name": "fuse.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/krisk/Fuse.git"
    },
    "scripts": {
        "build": "WEBPACK_ENV=build webpack && WEBPACK_ENV=dev webpack",
        "dev": "WEBPACK_ENV=dev webpack --progress --colors --watch",
        "test": "vows test/**.js"
    },
    "types": "./index.d.ts",
    "version": "2.7.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

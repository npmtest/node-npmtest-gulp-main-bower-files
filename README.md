# npmtest-gulp-main-bower-files

#### test coverage for  [gulp-main-bower-files (v1.6.2)](https://github.com/mauricedb/gulp-main-bower-files)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-main-bower-files.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-main-bower-files) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-main-bower-files.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-main-bower-files)

#### Use main-bower-files in a more gulp like way.

[![NPM](https://nodei.co/npm/gulp-main-bower-files.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-main-bower-files)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-main-bower-files/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-main-bower-files/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-main-bower-files/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-main-bower-files/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-main-bower-files/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-main-bower-files/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-main-bower-files/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Maurice de Beijer"
    },
    "bugs": {
        "url": "https://github.com/mauricedb/gulp-main-bower-files/issues"
    },
    "dependencies": {
        "gulp-util": "3.0.8",
        "main-bower-files": "2.13.1",
        "through2": "2.0.3"
    },
    "description": "Use main-bower-files in a more gulp like way.",
    "devDependencies": {
        "codecov.io": "0.1.6",
        "gulp": "3.9.1",
        "gulp-debug": "3.1.0",
        "gulp-mocha": "4.2.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "stream-assert": "2.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "42ee785af6b84df53c877faf3dd35a54e4853aaa",
        "tarball": "https://registry.npmjs.org/gulp-main-bower-files/-/gulp-main-bower-files-1.6.2.tgz"
    },
    "gitHead": "76d42d5a7f974d897b56eeab5d6f8956854763ee",
    "homepage": "https://github.com/mauricedb/gulp-main-bower-files",
    "keywords": [
        "gulp-main-bower-files",
        "gulp",
        "plugin",
        "gulpplugin",
        "main-bower-files"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mauricedb"
        }
    ],
    "name": "gulp-main-bower-files",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mauricedb/gulp-main-bower-files.git"
    },
    "scripts": {
        "report-coverage": "cat ./coverage/lcov.info | ./node_modules/.bin/codecov",
        "test": "istanbul cover ./node_modules/mocha/bin/_mocha",
        "test:watch": "mocha --watch"
    },
    "version": "1.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

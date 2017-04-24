# npmtest-timeago.js

#### basic test coverage for  [timeago.js (v3.0.1)](https://github.com/hustcc/timeago.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-timeago.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-timeago.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-timeago.js.svg)](https://travis-ci.org/npmtest/node-npmtest-timeago.js)

#### timeago.js is a simple library (only 2kb) to used to format datetime with `*** time ago` statement. eg: '3 hours ago'. localization supported.

[![NPM](https://nodei.co/npm/timeago.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/timeago.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-timeago.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-timeago.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-timeago.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-timeago.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-timeago.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-timeago.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-timeago.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-timeago.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-timeago.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-timeago.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-timeago.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-timeago.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-timeago.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-timeago.js/build/test-report.html](https://npmtest.github.io/node-npmtest-timeago.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-timeago.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-timeago.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-timeago.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-timeago.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-timeago.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-timeago.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-timeago.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-timeago.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "hustcc",
        "url": "http://git.hust.cc/timeago.js"
    },
    "bugs": {
        "url": "https://github.com/hustcc/timeago.js/issues"
    },
    "dependencies": {
        "@types/jquery": "^2.0.40"
    },
    "description": "timeago.js is a simple library (only 2kb) to used to format datetime with '*** time ago' statement. eg: '3 hours ago'. localization supported.",
    "devDependencies": {
        "gulp": "^3.9.0",
        "gulp-inject-version": "^1.0.1",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^2.0.0",
        "jshint": "^2.9.2",
        "slice.js": "^1.0.3",
        "tape": "^4.6.2",
        "typescript": "^2.2.1",
        "webpack": "^1.12.9"
    },
    "directories": {},
    "dist": {
        "shasum": "59b75e0c963bbadc34e0aca901f7430c053a0e1f",
        "tarball": "https://registry.npmjs.org/timeago.js/-/timeago.js-3.0.1.tgz"
    },
    "gitHead": "b90892dc1cd4bdeba98eaa038c92f39440102235",
    "homepage": "https://github.com/hustcc/timeago.js#readme",
    "keywords": [
        "timeago",
        "datetime",
        "*** time ago",
        "date",
        "javascript timeago"
    ],
    "license": "MIT",
    "main": "dist/timeago.min.js",
    "maintainers": [
        {
            "name": "atool"
        }
    ],
    "name": "timeago.js",
    "officialName": "timeago.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/hustcc/timeago.js.git"
    },
    "scripts": {
        "build": "gulp mini && webpack && npm run test",
        "lint": "jshint src/timeago.js",
        "test": "npm run lint && node tests/locales_test.js && node tests/test.js && npm run test_ts",
        "test_dev": "npm run lint && node tests/test_dev.js",
        "test_ts": "tsc tests/test_ts.ts --noImplicitAny && node tests/test_ts.js"
    },
    "summary": "timeago.js is a simple library (less than 2kb) to used to format datetime with '*** time ago' statement. eg: '3 hours ago'.",
    "typings": "./timeago.d.ts",
    "version": "3.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

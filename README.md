# npmtest-google-cdn

#### basic test coverage for  [google-cdn (v1.1.0)](https://github.com/passy/google-cdn)  [![npm package](https://img.shields.io/npm/v/npmtest-google-cdn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-google-cdn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-google-cdn.svg)](https://travis-ci.org/npmtest/node-npmtest-google-cdn)

#### Replaces references to resources on the Google CDN

[![NPM](https://nodei.co/npm/google-cdn.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/google-cdn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-google-cdn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-cdn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-google-cdn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-google-cdn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-google-cdn/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-google-cdn/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-google-cdn/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-google-cdn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-google-cdn/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-google-cdn/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-google-cdn/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-google-cdn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-google-cdn/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-google-cdn/build/test-report.html](https://npmtest.github.io/node-npmtest-google-cdn/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-google-cdn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-google-cdn/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-google-cdn/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-google-cdn/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-google-cdn/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-google-cdn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-google-cdn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-google-cdn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pascal Hartig",
        "url": "http://passy.me"
    },
    "bugs": {
        "url": "https://github.com/passy/google-cdn/issues"
    },
    "dependencies": {
        "async": "^1.4.2",
        "bower": "^1.4.1",
        "cdnjs-cdn-data": "~0.1.0",
        "debug": "^2.1.0",
        "escape-regexp": "0.0.1",
        "google-cdn-data": "~0.1.0",
        "regexp-quote": "0.0.0",
        "semver": "^5.0.1"
    },
    "description": "Replaces references to resources on the Google CDN",
    "devDependencies": {
        "chai": "^3.2.0",
        "escape-regexp": "0.0.1",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "mocha": "^2.0.1",
        "proxyquire": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "566f8e820c97e4af64605fd787c22ff91fc42830",
        "tarball": "https://registry.npmjs.org/google-cdn/-/google-cdn-1.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "files": [
        "googlecdn.js",
        "lib/",
        "util/"
    ],
    "gitHead": "1ca883db460cc687221e4e150e0ab28a2442985a",
    "homepage": "https://github.com/passy/google-cdn",
    "keywords": [
        "cdn",
        "google",
        "cdnjs"
    ],
    "license": "BSD-3-Clause",
    "licenses": [
        {
            "type": "BSD"
        }
    ],
    "main": "googlecdn.js",
    "maintainers": [
        {
            "name": "passy"
        },
        {
            "name": "btford"
        }
    ],
    "name": "google-cdn",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/passy/google-cdn.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

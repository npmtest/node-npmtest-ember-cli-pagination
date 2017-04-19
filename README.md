# npmtest-ember-cli-pagination

#### test coverage for  [ember-cli-pagination (v3.0.1)](https://github.com/mharris717/ember-cli-pagination#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-pagination.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-pagination) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-pagination.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-pagination)

#### Addon for Ember CLI to do simple pagination. Compatible with the kaminari API in Rails

[![NPM](https://nodei.co/npm/ember-cli-pagination.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-pagination)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-pagination/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-pagination/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-pagination/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-pagination/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-pagination/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-pagination/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-pagination/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-pagination/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bugs": {
        "url": "https://github.com/mharris717/ember-cli-pagination/issues"
    },
    "dependencies": {
        "ember-cli-babel": "^5.1.6",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-version-checker": "^1.1.5"
    },
    "description": "Addon for Ember CLI to do simple pagination. Compatible with the kaminari API in Rails",
    "devDependencies": {
        "active-model-adapter": "2.0.3",
        "bower": "^1.8.0",
        "broccoli-asset-rev": "^2.4.5",
        "ember-ajax": "^2.4.1",
        "ember-cli": "2.11.0",
        "ember-cli-app-version": "^2.0.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-shims": "^1.0.2",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.11.0",
        "ember-disable-proxy-controllers": "^1.0.1",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-source": "^2.11.0",
        "ember-try": "0.0.8",
        "express": "^4.12.4",
        "glob": "^5.0.14",
        "loader.js": "^4.0.10",
        "morgan": "^1.5.3",
        "phantomjs-prebuilt": "^2.1.14"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "8fbdec4184bee887df32d6b0de9a7216d86deec0",
        "tarball": "https://registry.npmjs.org/ember-cli-pagination/-/ember-cli-pagination-3.0.1.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "f8f03c6166273fab533d617a3fa8e06d699f2875",
    "homepage": "https://github.com/mharris717/ember-cli-pagination#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "mharris717"
        }
    ],
    "name": "ember-cli-pagination",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mharris717/ember-cli-pagination.git"
    },
    "scripts": {
        "build": "ember build",
        "clean": "rm -Rf ./node_modules ./bower_components",
        "setup": "npm install && bower install",
        "test": "ember try:testall"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

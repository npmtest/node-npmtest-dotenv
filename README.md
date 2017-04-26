# npmtest-dotenv

#### basic test coverage for  [dotenv (v4.0.0)](https://github.com/motdotla/dotenv#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dotenv.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dotenv) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dotenv.svg)](https://travis-ci.org/npmtest/node-npmtest-dotenv)

#### Loads environment variables from .env file

[![NPM](https://nodei.co/npm/dotenv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dotenv)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dotenv/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dotenv/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dotenv/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dotenv/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dotenv/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-dotenv/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-dotenv/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dotenv/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dotenv/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dotenv/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dotenv/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dotenv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dotenv/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dotenv/build/test-report.html](https://npmtest.github.io/node-npmtest-dotenv/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dotenv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dotenv/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dotenv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dotenv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dotenv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dotenv/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dotenv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dotenv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "scottmotte"
    },
    "bugs": {
        "url": "https://github.com/motdotla/dotenv/issues"
    },
    "dependencies": {},
    "description": "Loads environment variables from .env file",
    "devDependencies": {
        "babel": "5.8.23",
        "coveralls": "^2.11.9",
        "lab": "11.1.0",
        "semver": "5.3.0",
        "should": "11.1.1",
        "sinon": "1.17.6",
        "standard": "8.4.0",
        "standard-markdown": "2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "864ef1379aced55ce6f95debecdce179f7a0cd1d",
        "tarball": "https://registry.npmjs.org/dotenv/-/dotenv-4.0.0.tgz"
    },
    "engines": {
        "node": ">=4.6.0"
    },
    "gitHead": "fdd0923e82e12a6e29b65898990201857141e75d",
    "homepage": "https://github.com/motdotla/dotenv#readme",
    "keywords": [
        "dotenv",
        "env",
        ".env",
        "environment",
        "variables",
        "config",
        "settings"
    ],
    "license": "BSD-2-Clause",
    "main": "lib/main.js",
    "maintainers": [
        {
            "name": "jcblw"
        },
        {
            "name": "maxbeatty"
        },
        {
            "name": "motdotla"
        },
        {
            "name": "scottmotte"
        }
    ],
    "name": "dotenv",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/motdotla/dotenv.git"
    },
    "scripts": {
        "lint": "standard",
        "lint-md": "standard-markdown",
        "postlint": "npm run lint-md",
        "pretest": "npm run lint",
        "test": "lab test/* -r lcov | coveralls"
    },
    "version": "4.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

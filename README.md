# test coverage for  [husky (v0.13.3)](https://github.com/typicode/husky)  [![npm package](https://img.shields.io/npm/v/npmtest-husky.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-husky) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-husky.svg)](https://travis-ci.org/npmtest/node-npmtest-husky)
#### Prevents bad commit or push (git hooks, pre-commit/precommit, pre-push/prepush, post-merge/postmerge and all that stuff...)

[![NPM](https://nodei.co/npm/husky.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/husky)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-husky/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-husky/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-husky/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-husky/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-husky/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-husky/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-husky/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-husky/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-husky/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-husky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-husky/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-husky/build/test-report.html](https://npmtest.github.io/node-npmtest-husky/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-husky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-husky/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-husky/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-husky/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-husky/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-husky/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-husky/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-husky/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Typicode"
    },
    "bugs": {
        "url": "https://github.com/typicode/husky/issues"
    },
    "dependencies": {
        "chalk": "^1.1.3",
        "find-parent-dir": "^0.3.0",
        "is-ci": "^1.0.9",
        "normalize-path": "^1.0.0"
    },
    "description": "Prevents bad commit or push (git hooks, pre-commit/precommit, pre-push/prepush, post-merge/postmerge and all that stuff...)",
    "devDependencies": {
        "expect": "^1.20.2",
        "mocha": "^3.2.0",
        "mock-fs": "^3.12.1",
        "pkg-ok": "^1.0.1",
        "rimraf": "^2.2.8",
        "standard": "^8.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bc2066080badc8b8fe3516e881f5bc68a57052ff",
        "tarball": "https://registry.npmjs.org/husky/-/husky-0.13.3.tgz"
    },
    "gitHead": "4b5011e854c0bccf384805107233bc72db77d9a8",
    "homepage": "https://github.com/typicode/husky",
    "keywords": [
        "git",
        "hook",
        "hooks",
        "pre-commit",
        "precommit",
        "post-commit",
        "postcommit",
        "pre-push",
        "prepush",
        "post-merge",
        "postmerge",
        "test"
    ],
    "license": "MIT",
    "main": "./src/index.js",
    "maintainers": [
        {
            "name": "typicode"
        }
    ],
    "name": "husky",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/typicode/husky.git"
    },
    "scripts": {
        "install": "node ./bin/install.js",
        "precommit": "npm test",
        "prepublish": "pkg-ok",
        "test": "mocha && standard",
        "uninstall": "node ./bin/uninstall.js"
    },
    "standard": {
        "env": {
            "mocha": true
        }
    },
    "version": "0.13.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

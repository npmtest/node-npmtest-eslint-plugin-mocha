# test coverage for  [eslint-plugin-mocha (v4.9.0)](https://github.com/lo1tuma/eslint-plugin-mocha)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-mocha.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-mocha)
#### Eslint rules for mocha.

[![NPM](https://nodei.co/npm/eslint-plugin-mocha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-mocha)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-mocha/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-mocha/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-mocha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-mocha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-mocha/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Schreck"
    },
    "bugs": {
        "url": "https://github.com/lo1tuma/eslint-plugin-mocha/issues"
    },
    "contributors": [
        {
            "name": "Alexander Schmidt"
        }
    ],
    "dependencies": {
        "ramda": "^0.23.0"
    },
    "description": "Eslint rules for mocha.",
    "devDependencies": {
        "chai": "^3.5.0",
        "coveralls": "^2.11.6",
        "eslint": "^3.0.0",
        "istanbul": "^0.4.2",
        "mocha": "^3.0.0",
        "pr-log": "^1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "917a8b499ab8d0c01d69c6e4f81d362ee099b6fd",
        "tarball": "https://registry.npmjs.org/eslint-plugin-mocha/-/eslint-plugin-mocha-4.9.0.tgz"
    },
    "gitHead": "b6a189f17b76e69b10cd7bf880267d54335dc2f7",
    "homepage": "https://github.com/lo1tuma/eslint-plugin-mocha",
    "keywords": [
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "mocha"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jfmengels"
        },
        {
            "name": "lo1tuma"
        },
        {
            "name": "lxanders"
        }
    ],
    "name": "eslint-plugin-mocha",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "^2.0.0 || ^3.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/lo1tuma/eslint-plugin-mocha.git"
    },
    "scripts": {
        "changelog": "pr-log",
        "check-coverage": "istanbul check-coverage --statement 100 --branch 100 --function 100 --lines 100",
        "coveralls": "cat ./build/coverage/lcov.info | coveralls",
        "pretest": "eslint .",
        "test": "npm run test:unit --coverage && npm run check-coverage",
        "test:unit": "istanbul test _mocha test -- --recursive --reporter dot"
    },
    "version": "4.9.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

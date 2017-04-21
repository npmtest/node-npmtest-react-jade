# npmtest-react-jade

#### basic test coverage for  [react-jade (v2.5.0)](https://github.com/jadejs/react-jade)  [![npm package](https://img.shields.io/npm/v/npmtest-react-jade.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-jade) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-jade.svg)](https://travis-ci.org/npmtest/node-npmtest-react-jade)

#### Compile Jade to React JavaScript

[![NPM](https://nodei.co/npm/react-jade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-jade)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-jade/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-jade/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-jade/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-jade/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-jade/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-jade/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-jade/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-jade/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-jade/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-jade/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-jade/build/test-report.html](https://npmtest.github.io/node-npmtest-react-jade/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-jade/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-jade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-jade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ForbesLindesay"
    },
    "bugs": {
        "url": "https://github.com/jadejs/react-jade/issues"
    },
    "dependencies": {
        "acorn": "^1.1.0",
        "constantinople": "^3.0.1",
        "ent": "^2.2.0",
        "jade": "1.9.2",
        "js-stringify": "^1.0.1",
        "resolve": "^1.1.6",
        "static-module": "^1.1.2",
        "uglify-js": "^2.4.21",
        "with": "^5.0.0"
    },
    "description": "Compile Jade to React JavaScript",
    "devDependencies": {
        "es6ify": "^1.6.0",
        "gethub": "^2.0.1",
        "htmlparser2": "^3.8.2",
        "istanbul": "^0.3.14",
        "marked": "^0.3.3",
        "react": "^0.14.0",
        "react-dom": "^0.14.0",
        "rimraf": "^2.3.3",
        "testit": "^2.0.2",
        "unescape-html": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c34d9d2dd3eea01f52fd49cc288a5c1a687c948c",
        "tarball": "https://registry.npmjs.org/react-jade/-/react-jade-2.5.0.tgz"
    },
    "gitHead": "deee1553bb57c32ea4590a7a32ad4026a2b49218",
    "homepage": "https://github.com/jadejs/react-jade",
    "keywords": [],
    "license": "MIT",
    "maintainers": [
        {
            "name": "forbeslindesay"
        },
        {
            "name": "jeromew"
        }
    ],
    "name": "react-jade",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": ">=0.12.0 <0.15.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jadejs/react-jade.git"
    },
    "scripts": {
        "coverage": "istanbul cover test",
        "test": "node test/download-jade-tests.js && node test/index.js && npm run coverage"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

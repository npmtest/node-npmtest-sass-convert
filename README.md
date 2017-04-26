# npmtest-sass-convert

#### basic test coverage for  [sass-convert (v0.5.2)](https://github.com/SassDoc/sass-convert)  [![npm package](https://img.shields.io/npm/v/npmtest-sass-convert.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sass-convert) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sass-convert.svg)](https://travis-ci.org/npmtest/node-npmtest-sass-convert)

#### Node.js bindings to sass-convert

[![NPM](https://nodei.co/npm/sass-convert.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sass-convert)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sass-convert/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sass-convert/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sass-convert/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sass-convert/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sass-convert/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-sass-convert/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-sass-convert/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sass-convert/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sass-convert/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sass-convert/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sass-convert/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sass-convert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sass-convert/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sass-convert/build/test-report.html](https://npmtest.github.io/node-npmtest-sass-convert/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sass-convert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sass-convert/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sass-convert/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sass-convert/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sass-convert/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sass-convert/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sass-convert/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sass-convert/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pascal Duez",
        "url": "https://github.com/pascalduez"
    },
    "bugs": {
        "url": "https://github.com/SassDoc/sass-convert/issues"
    },
    "contributors": [
        {
            "name": "Valérian Galliat",
            "url": "https://twitter.com/valeriangalliat"
        },
        {
            "name": "Fabrice Weinberg",
            "url": "https://twitter.com/fweinb"
        },
        {
            "name": "Hugo Giraudel",
            "url": "https://twitter.com/HugoGiraudel"
        }
    ],
    "dependencies": {
        "concat-stream": "^1.4.7",
        "dargs": "^4.0.0",
        "ends-with": "^0.2.0",
        "es6-denodeify": "^0.1.0",
        "es6-promise": "^3.0.2",
        "memoize-decorator": "^1.0.2",
        "object-assign": "^3.0.0",
        "semver": "^5.0.1",
        "semver-regex": "^1.0.0",
        "through2": "^2.0.0",
        "which": "^1.0.5"
    },
    "description": "Node.js bindings to sass-convert",
    "devDependencies": {
        "babel": "^5.8.21",
        "babel-eslint": "^4.0.10",
        "chalk": "^1.0.0",
        "coveralls": "^2.11.2",
        "dateformat": "^1.0.11",
        "eslint": "^1.1.0",
        "faucet": "0.0.1",
        "gulp-rename": "^1.2.0",
        "istanbul": "^0.3.5",
        "readdirp": "^1.3.0",
        "rimraf": "^2.2.8",
        "tape": "^4.2.0",
        "vinyl-fs": "^1.0.0",
        "vinyl-source-stream": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b1ed42b0e8d6fe98ec7ed6e78a38e26564860f06",
        "tarball": "https://registry.npmjs.org/sass-convert/-/sass-convert-0.5.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=2.1.0"
    },
    "files": [
        "bin",
        "dist",
        "CHANGELOG.md",
        "index.js",
        "README.md",
        "UNLICENSE"
    ],
    "gitHead": "d77702183c502c7987a8d879ed7dab605840e931",
    "homepage": "https://github.com/SassDoc/sass-convert",
    "keywords": [
        "sass",
        "scss",
        "css",
        "convertion"
    ],
    "license": "Unlicense",
    "maintainers": [
        {
            "name": "pascalduez"
        },
        {
            "name": "valeriangalliat"
        },
        {
            "name": "fweinb"
        },
        {
            "name": "hugogiraudel"
        }
    ],
    "name": "sass-convert",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/SassDoc/sass-convert.git"
    },
    "scripts": {
        "test": "make dist test"
    },
    "version": "0.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-unistyle

#### test coverage for  [unistyle (v0.4.0)](https://github.com/joakimbeng/unistyle#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-unistyle.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-unistyle) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-unistyle.svg)](https://travis-ci.org/npmtest/node-npmtest-unistyle)

#### Write modular and scalable CSS using the next version of ECMAScript.

[![NPM](https://nodei.co/npm/unistyle.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/unistyle)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-unistyle/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-unistyle/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-unistyle/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-unistyle/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-unistyle/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-unistyle/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-unistyle/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-unistyle/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-unistyle/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-unistyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-unistyle/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-unistyle/build/test-report.html](https://npmtest.github.io/node-npmtest-unistyle/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-unistyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-unistyle/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-unistyle/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-unistyle/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-unistyle/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-unistyle/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-unistyle/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-unistyle/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Joakim Carlstein"
    },
    "babel": {
        "presets": [
            "es2015",
            "stage-2"
        ]
    },
    "bin": {
        "unistyle": "bin/unistyle"
    },
    "bugs": {
        "url": "https://github.com/joakimbeng/unistyle/issues"
    },
    "dependencies": {
        "kebab-case": "^1.0.0",
        "meow": "^3.7.0",
        "pify": "^2.2.0",
        "pixelify": "^2.0.1",
        "to-css": "^1.2.1",
        "unistyle-flat": "^1.1.1"
    },
    "description": "Write modular and scalable CSS using the next version of ECMAScript.",
    "devDependencies": {
        "ava": "^0.11.0",
        "babel-cli": "^6.4.5",
        "babel-core": "^6.4.5",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-2": "^6.3.13",
        "classnameify": "^1.0.0",
        "os-tmpdir": "^1.0.1",
        "promise-all": "^1.0.0",
        "xo": "^0.12.1"
    },
    "directories": {
        "test": "test",
        "example": "examples"
    },
    "dist": {
        "shasum": "d947cebd2d0ecae02e2604727440814a9e69c875",
        "tarball": "https://registry.npmjs.org/unistyle/-/unistyle-0.4.0.tgz"
    },
    "gitHead": "4d5f00e75a6e1ec1cfabbab04815d455fc14d96a",
    "homepage": "https://github.com/joakimbeng/unistyle#readme",
    "keywords": [
        "css",
        "styles",
        "stylesheet",
        "ecmascript",
        "es6",
        "es2015",
        "es7",
        "es2016",
        "universal javascript",
        "isomorphic",
        "no-cascade",
        "scalable",
        "large scale"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "joakimbeng"
        }
    ],
    "name": "unistyle",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/joakimbeng/unistyle.git"
    },
    "scripts": {
        "compile:examples": "babel --ignore 'examples/react/*/button.js' examples -d examples-es5",
        "compile:fixtures": "babel test/fixtures -d test/fixtures-es5",
        "lint": "xo",
        "precompile:fixtures": "rm -rf test/fixtures-es5",
        "pretest": "npm run -s lint && npm run -s compile:fixtures",
        "test": "ava --verbose 'test/*-test.js'"
    },
    "version": "0.4.0",
    "xo": {
        "space": true,
        "ignores": [
            "test/fixtures/**",
            "test/fixtures-es5/**",
            "examples/**",
            "examples-es5/**"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

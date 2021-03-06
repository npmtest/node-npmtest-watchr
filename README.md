# npmtest-watchr

#### basic test coverage for  [watchr (v3.0.1)](https://github.com/bevry/watchr)  [![npm package](https://img.shields.io/npm/v/npmtest-watchr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-watchr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-watchr.svg)](https://travis-ci.org/npmtest/node-npmtest-watchr)

#### Better file system watching for Node.js

[![NPM](https://nodei.co/npm/watchr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/watchr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-watchr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-watchr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-watchr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-watchr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-watchr/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-watchr/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-watchr/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-watchr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-watchr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-watchr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-watchr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-watchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-watchr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-watchr/build/test-report.html](https://npmtest.github.io/node-npmtest-watchr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-watchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-watchr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-watchr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-watchr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-watchr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-watchr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-watchr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-watchr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "2012+ Bevry Pty Ltd",
        "url": "http://bevry.me"
    },
    "badges": {
        "list": [
            "travisci",
            "npmversion",
            "npmdownloads",
            "daviddm",
            "daviddmdev",
            "---",
            "slackin",
            "patreon",
            "gratipay",
            "flattr",
            "paypal",
            "bitcoin",
            "wishlist"
        ],
        "config": {
            "patreonUsername": "bevry",
            "gratipayUsername": "bevry",
            "flattrUsername": "balupton",
            "paypalURL": "https://bevry.me/paypal",
            "bitcoinURL": "https://bevry.me/bitcoin",
            "wishlistURL": "https://bevry.me/wishlist",
            "slackinURL": "https://slack.bevry.me"
        }
    },
    "bugs": {
        "url": "https://github.com/bevry/watchr/issues"
    },
    "contributors": [
        {
            "name": "Benjamin Lupton",
            "url": "http://balupton.com"
        },
        {
            "name": "Aaron O'Mullan",
            "url": "http://www.gitbook.com"
        },
        {
            "name": "Adam Sanderson",
            "url": "monkeyandcrow.com"
        },
        {
            "name": "Casey Foster",
            "url": "http://ca.sey.me"
        },
        {
            "name": "Fredrik Norén",
            "url": "https://github.com/FredrikNoren"
        },
        {
            "name": "Robson Roberto Souza Peixoto",
            "url": "https://github.com/robsonpeixoto"
        },
        {
            "name": "Stuart Knightley",
            "url": "http://stuartk.com/"
        },
        {
            "name": "David Byrd",
            "url": "http://digitalocean.com"
        },
        {
            "name": "Josh Levine",
            "url": "https://github.com/jlevine22"
        }
    ],
    "dependencies": {
        "eachr": "^3.2.0",
        "editions": "^1.3.1",
        "extendr": "^3.2.2",
        "ignorefs": "^1.1.1",
        "safefs": "^4.1.0",
        "scandirectory": "^2.5.0",
        "taskgroup": "^5.0.1"
    },
    "description": "Better file system watching for Node.js",
    "devDependencies": {
        "assert-helpers": "^4.4.0",
        "babel-cli": "^6.16.0",
        "babel-preset-es2015": "^6.16.0",
        "bal-util": "^2.6.0",
        "core-js": "^2.4.1",
        "documentation": "^4.0.0-beta11",
        "eslint": "^3.8.1",
        "flow-bin": "^0.33.0",
        "joe": "^1.8.0",
        "joe-reporter-console": "^1.2.1",
        "projectz": "^1.3.0",
        "rimraf": "^2.5.4"
    },
    "directories": {},
    "dist": {
        "shasum": "3b7e078160d12484481d81a8640d5fd880408540",
        "tarball": "https://registry.npmjs.org/watchr/-/watchr-3.0.1.tgz"
    },
    "editions": [
        {
            "description": "Source + ESNext + Require + Flow Type Comments",
            "entry": "index.js",
            "directory": "source",
            "syntaxes": [
                "javascript",
                "esnext",
                "require",
                "arrows",
                "getset",
                "const",
                "let",
                "classes",
                "defaults",
                "spread",
                "rest",
                "destructuring",
                "template strings",
                "flow type comments"
            ]
        },
        {
            "description": "Babel Compiled + ES2015 + Require",
            "entry": "index.js",
            "directory": "es2015",
            "syntaxes": [
                "javascript",
                "es2015",
                "require"
            ]
        }
    ],
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "782e194fe7e3122173c21a690bc8f6f041da0b1c",
    "homepage": "https://github.com/bevry/watchr",
    "keywords": [
        "watching",
        "watch",
        "fswatcher",
        "watchfile",
        "fs"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "balupton"
        }
    ],
    "name": "watchr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/bevry/watchr.git"
    },
    "scripts": {
        "our:clean": "rm -Rf ./docs ./es2015",
        "our:compile": "npm run our:compile:es2015",
        "our:compile:es2015": "babel ./source --out-dir ./es2015 --presets es2015",
        "our:meta": "npm run our:meta:docs && npm run our:meta:projectz",
        "our:meta:docs": "documentation build -f html -o ./docs -g --shallow ./source/**.js",
        "our:meta:projectz": "projectz compile",
        "our:release": "npm run our:release:prepare && npm run our:release:publish && npm run our:release:tag && npm run our:release:push",
        "our:release:prepare": "npm run our:clean && npm run our:compile && npm run our:test && npm run our:meta",
        "our:release:publish": "npm publish",
        "our:release:push": "git push origin master && git push origin --tags",
        "our:release:tag": "git tag v$npm_package_version -a",
        "our:test": "npm run our:verify && npm test",
        "our:verify": "npm run our:verify:eslint && npm run our:verify:flow",
        "our:verify:eslint": "eslint --fix ./source",
        "our:verify:flow": "flow check",
        "test": "node --harmony ./test.js"
    },
    "version": "3.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

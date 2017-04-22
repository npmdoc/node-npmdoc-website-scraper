# npmdoc-website-scraper

#### api documentation for  [website-scraper (v2.3.0)](https://github.com/s0ph1e/node-website-scraper)  [![npm package](https://img.shields.io/npm/v/npmdoc-website-scraper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-website-scraper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-website-scraper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-website-scraper)

#### Download website to a local directory (including all css, images, js, etc.)

[![NPM](https://nodei.co/npm/website-scraper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/website-scraper)

- [https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-website-scraper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-website-scraper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-website-scraper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-website-scraper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sophia Antipenko"
    },
    "bugs": {
        "url": "https://github.com/s0ph1e/node-website-scraper/issues"
    },
    "dependencies": {
        "bluebird": "^3.0.1",
        "cheerio": "0.22.0",
        "css-url-parser": "^1.0.0",
        "debug": "^2.4.5",
        "fs-extra": "^2.0.0",
        "he": "^1.1.0",
        "lodash": "^4.11.1",
        "normalize-url": "^1.5.3",
        "request": "^2.42.0",
        "srcset": "^1.0.0"
    },
    "description": "Download website to a local directory (including all css, images, js, etc.)",
    "devDependencies": {
        "codeclimate-test-reporter": "^0.4.0",
        "coveralls": "^2.11.8",
        "eslint": "^3.9.1",
        "istanbul": "^0.4.0",
        "mocha": "^3.0.2",
        "nock": "^9.0.2",
        "proxyquire": "^1.7.3",
        "should": "^11.1.0",
        "sinon": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2b4821fb79bfa5d0aaf61e4de2eb58ba5a5873cc",
        "tarball": "https://registry.npmjs.org/website-scraper/-/website-scraper-2.3.0.tgz"
    },
    "gitHead": "978a31168531236112eb7dc598f5d4dde1e26a0c",
    "homepage": "https://github.com/s0ph1e/node-website-scraper",
    "keywords": [
        "scrape",
        "scraper",
        "download",
        "web",
        "url",
        "page",
        "site",
        "html",
        "css",
        "image",
        "js"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "s0ph1e"
        }
    ],
    "name": "website-scraper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/s0ph1e/node-website-scraper.git"
    },
    "scripts": {
        "eslint": "eslint lib/** index.js",
        "test": "istanbul cover node_modules/mocha/bin/_mocha --dir ./coverage --report lcov -- -R spec --recursive --timeout 7000 ./test/unit/ ./test/functional && npm run eslint",
        "test-e2e": "node_modules/mocha/bin/_mocha --timeout 300000 ./test/e2e/*-test.js"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

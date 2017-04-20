# npmdoc-pkgfiles

#### api documentation for  [pkgfiles (v2.3.2)](https://github.com/timoxley/pkgfiles)  [![npm package](https://img.shields.io/npm/v/npmdoc-pkgfiles.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pkgfiles) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pkgfiles.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pkgfiles)

#### List all files which would be published in a package.

[![NPM](https://nodei.co/npm/pkgfiles.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pkgfiles)

- [https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "pkgfiles",
    "version": "2.3.2",
    "description": "List all files which would be published in a package.",
    "main": "index.js",
    "bin": {
        "pkgfiles": "bin/pkgfiles.js"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "keywords": [
        "npm",
        "publish",
        "dependencies",
        "files",
        "package"
    ],
    "author": "Tim Oxley <secoif@gmail.com>",
    "license": "MIT",
    "dependencies": {
        "columnify": "^1.5.4",
        "du": "^0.1.0",
        "fstream-npm": "^1.2.0",
        "map-limit": "0.0.1",
        "minimist": "^1.2.0",
        "pkgresolve": "^1.1.4",
        "pretty-bytes": "^4.0.2"
    },
    "devDependencies": {
        "tape": "~4.6.3"
    },
    "directories": {
        "test": "test"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/timoxley/pkgfiles.git"
    },
    "bugs": {
        "url": "https://github.com/timoxley/pkgfiles/issues"
    },
    "homepage": "https://github.com/timoxley/pkgfiles"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

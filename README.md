# npmdoc-pkgfiles

#### basic api documentation for  [pkgfiles (v2.3.2)](https://github.com/timoxley/pkgfiles)  [![npm package](https://img.shields.io/npm/v/npmdoc-pkgfiles.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pkgfiles) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pkgfiles.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pkgfiles)

#### List all files which would be published in a package.

[![NPM](https://nodei.co/npm/pkgfiles.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pkgfiles)

- [https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pkgfiles/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Oxley"
    },
    "bin": {
        "pkgfiles": "bin/pkgfiles.js"
    },
    "bugs": {
        "url": "https://github.com/timoxley/pkgfiles/issues"
    },
    "dependencies": {
        "columnify": "^1.5.4",
        "du": "^0.1.0",
        "fstream-npm": "^1.2.0",
        "map-limit": "0.0.1",
        "minimist": "^1.2.0",
        "pkgresolve": "^1.1.4",
        "pretty-bytes": "^4.0.2"
    },
    "description": "List all files which would be published in a package.",
    "devDependencies": {
        "tape": "~4.6.3"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "1b54a7a8dbe32caa84b0955f44917e1500d33d05",
        "tarball": "https://registry.npmjs.org/pkgfiles/-/pkgfiles-2.3.2.tgz"
    },
    "gitHead": "8e60f04b05a7cb2ed22d709fe5369f07f3ba3b08",
    "homepage": "https://github.com/timoxley/pkgfiles",
    "keywords": [
        "npm",
        "publish",
        "dependencies",
        "files",
        "package"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "timoxley"
        }
    ],
    "name": "pkgfiles",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/timoxley/pkgfiles.git"
    },
    "scripts": {
        "test": "tape test/*.js"
    },
    "version": "2.3.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

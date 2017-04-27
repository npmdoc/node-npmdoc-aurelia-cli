# npmdoc-aurelia-cli

#### basic api documentation for  [aurelia-cli (v0.29.0)](http://aurelia.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-aurelia-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-aurelia-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-aurelia-cli.svg)](https://travis-ci.org/npmdoc/node-npmdoc-aurelia-cli)

#### The command line tooling for Aurelia.

[![NPM](https://nodei.co/npm/aurelia-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/aurelia-cli)

- [https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-aurelia-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Eisenberg",
        "url": "http://robeisenberg.com/"
    },
    "bin": {
        "aurelia": "bin/aurelia-cli.js",
        "au": "bin/aurelia-cli.js"
    },
    "bugs": {
        "url": "https://github.com/aurelia/cli/issues"
    },
    "dependencies": {
        "aurelia-dependency-injection": "^1.0.0",
        "aurelia-logging": "^1.2.0",
        "aurelia-polyfills": "^1.0.0",
        "esprima": "^3.1.3",
        "glob": "^7.1.1",
        "npm": "^3.10.8",
        "rfc6902": "^1.2.2",
        "semver": "^5.3.0"
    },
    "description": "The command line tooling for Aurelia.",
    "devDependencies": {
        "aurelia-tools": "^0.2.4",
        "babel-eslint": "^7.1.1",
        "gulp": "^3.9.1",
        "gulp-bump": "^2.7.0",
        "gulp-conventional-changelog": "^1.1.3",
        "gulp-eslint": "^3.0.1",
        "jasmine": "^2.5.2",
        "mock-fs": "^4.2.0",
        "nodemon": "^1.11.0",
        "require-dir": "^0.3.1",
        "run-sequence": "^1.2.2",
        "yargs": "^7.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "b261263d41ec4f09452873e82553fd2c816370bd",
        "tarball": "https://registry.npmjs.org/aurelia-cli/-/aurelia-cli-0.29.0.tgz"
    },
    "gitHead": "9bfe9bcbe30564a30090b42290fa2711590b96a8",
    "homepage": "http://aurelia.io",
    "keywords": [
        "aurelia",
        "cli",
        "bundle",
        "scaffold"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "ahmedshuhel"
        },
        {
            "name": "aureliaeffect"
        }
    ],
    "name": "aurelia-cli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aurelia/cli.git"
    },
    "scripts": {
        "test": "jasmine",
        "test:watch": "nodemon -x 'npm test'"
    },
    "version": "0.29.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

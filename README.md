# npmdoc-tabtab

#### api documentation for  [tabtab (v2.2.2)](https://github.com/mklabs/node-tabtab#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-tabtab.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-tabtab) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-tabtab.svg)](https://travis-ci.org/npmdoc/node-npmdoc-tabtab)

#### tab completion helpers, for node cli programs. Inspired by npm completion.

[![NPM](https://nodei.co/npm/tabtab.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/tabtab)

- [https://npmdoc.github.io/node-npmdoc-tabtab/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-tabtab/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-tabtab/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-tabtab/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-tabtab/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-tabtab/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mklabs"
    },
    "bin": {
        "tabtab": "bin/tabtab"
    },
    "bugs": {
        "url": "https://github.com/mklabs/node-tabtab/issues"
    },
    "dependencies": {
        "debug": "^2.2.0",
        "inquirer": "^1.0.2",
        "lodash.difference": "^4.5.0",
        "lodash.uniq": "^4.5.0",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "npmlog": "^2.0.3",
        "object-assign": "^4.1.0"
    },
    "description": "tab completion helpers, for node cli programs. Inspired by npm completion.",
    "devDependencies": {
        "babel-cli": "^6.7.5",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-preset-es2015": "^6.6.0",
        "eslint": "^2.8.0",
        "gentle-cli": "^1.0.3",
        "jscs": "^3.0.3",
        "mocha": "^2.4.5",
        "standard-version": "^2.1.2",
        "watchd": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7a047f143b010b4cbd31f857e82961512cbf4e14",
        "tarball": "https://registry.npmjs.org/tabtab/-/tabtab-2.2.2.tgz"
    },
    "gitHead": "fcb0a3662e0b611bf82959ebd3b67604712eeddd",
    "homepage": "https://github.com/mklabs/node-tabtab#readme",
    "keywords": [
        "terminal",
        "tab",
        "unix",
        "console",
        "complete",
        "completion"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mklabs"
        }
    ],
    "name": "tabtab",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mklabs/node-tabtab.git"
    },
    "scripts": {
        "babel": "babel lib/ -d src/",
        "changelog": "standard-version -m '%s'",
        "prepublish": "npm run babel",
        "pretest": "npm run babel",
        "release": "standard-version -m '%s' && git push origin master --tags && npm publish",
        "test": "SHELL=zsh babel-node ./node_modules/.bin/mocha test",
        "watch": "watchd lib/* -c 'npm run babel'"
    },
    "version": "2.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

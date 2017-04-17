# api documentation for  [posthtml (v0.9.2)](https://github.com/posthtml/posthtml)  [![npm package](https://img.shields.io/npm/v/npmdoc-posthtml.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-posthtml) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-posthtml.svg)](https://travis-ci.org/npmdoc/node-npmdoc-posthtml)
#### HTML/XML processor

[![NPM](https://nodei.co/npm/posthtml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/posthtml)

- [https://npmdoc.github.io/node-npmdoc-posthtml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-posthtml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-posthtml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-posthtml/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-posthtml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-posthtml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Anton Winogradov"
    },
    "bugs": {
        "url": "https://github.com/posthtml/posthtml/issues"
    },
    "contributors": [
        {
            "name": "Ivan Voischev"
        },
        {
            "name": "Anton Winogradov"
        },
        {
            "name": "Alexej Yaroshevich"
        }
    ],
    "dependencies": {
        "posthtml-parser": "^0.2.0",
        "posthtml-render": "^1.0.5"
    },
    "description": "HTML/XML processor",
    "devDependencies": {
        "chai": "^3.0.0",
        "chai-as-promised": "^6.0.0",
        "chai-subset": "^1.1.0",
        "conventional-changelog-cli": "^1.0.0",
        "es6-promise": "^4.0.5",
        "istanbul": "^0.4.2",
        "jsdoc-to-markdown": "^2.0.0",
        "mocha": "^3.1.2",
        "mversion": "^1.10.0",
        "object.assign": "^4.0.3",
        "standard": "^8.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f4c06db9f67b61fd17c4e256e7e3d9515bf726fd",
        "tarball": "https://registry.npmjs.org/posthtml/-/posthtml-0.9.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "aa7c848a16defe8cd7a57f241bd889df4a4cc1ad",
    "homepage": "https://github.com/posthtml/posthtml",
    "keywords": [
        "html",
        "xml",
        "postproccessor",
        "parser",
        "transform",
        "transformations",
        "manipulation",
        "preprocessor",
        "processor"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "qfox"
        },
        {
            "name": "scrum"
        },
        {
            "name": "verybigman"
        },
        {
            "name": "voischev"
        }
    ],
    "name": "posthtml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/posthtml/posthtml.git"
    },
    "scripts": {
        "clean": "rm -rf coverage jsdoc-api",
        "cover": "istanbul cover --report text --report html --report lcov node_modules/mocha/bin/_mocha -- -R tap",
        "docs:api": "jsdoc2md lib/api.js > docs/api.md",
        "docs:core": "jsdoc2md lib/index.js > docs/core.md",
        "lint": "standard",
        "release:major": "mversion major",
        "release:minor": "mversion minor",
        "release:patch": "mversion patch",
        "test": "npm run lint && mocha -R dot && npm run cover"
    },
    "version": "0.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

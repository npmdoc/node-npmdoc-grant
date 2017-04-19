# npmdoc-grant

#### api documentation for  [grant (v3.7.1)](https://github.com/simov/grant)  [![npm package](https://img.shields.io/npm/v/npmdoc-grant.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grant) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grant.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grant)

#### OAuth Middleware for Express, Koa and Hapi

[![NPM](https://nodei.co/npm/grant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grant)

- [https://npmdoc.github.io/node-npmdoc-grant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grant/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Simeon Velichkov",
        "url": "http://simov.github.io"
    },
    "bugs": {
        "url": "https://github.com/simov/grant/issues"
    },
    "dependencies": {
        "deep-copy": "^1.1.2",
        "qs": "6.2.1",
        "request": "2.74.0"
    },
    "description": "OAuth Middleware for Express, Koa and Hapi",
    "devDependencies": {
        "body-parser": "^1.15.0",
        "coveralls": "^2.11.9",
        "eslint": "^2.9.0",
        "eslint-config-standard": "^5.2.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.2",
        "express": "^4.13.4",
        "express-session": "^1.13.0",
        "hapi": "9.3.1",
        "istanbul": "^0.4.2",
        "koa": "^1.2.0",
        "koa-bodyparser": "^2.0.1",
        "koa-mount": "^1.3.0",
        "koa-qs": "^2.0.0",
        "koa-route": "^2.4.2",
        "koa-session": "^3.3.1",
        "mocha": "^2.4.5",
        "thunkify": "^2.1.2",
        "yar": "4.x.x"
    },
    "directories": {},
    "dist": {
        "shasum": "d59f29a59fd22e8f5435232d92f47c048761d5f9",
        "tarball": "https://registry.npmjs.org/grant/-/grant-3.7.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "config/",
        "lib/",
        "CHANGELOG.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "057e9224308191b91c9e4b6fdf5896284c85d355",
    "homepage": "https://github.com/simov/grant",
    "keywords": [
        "oauth",
        "oauth2",
        "authentication",
        "middleware",
        "express",
        "koa",
        "hapi"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "simov"
        }
    ],
    "name": "grant",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/simov/grant.git"
    },
    "scripts": {
        "lint": "eslint lib/ test/ examples/ && echo Lint Passed",
        "test": "npm run lint && npm run test-ci",
        "test-ci": "mocha --recursive test/",
        "test-cov": "istanbul cover _mocha -- --recursive test/"
    },
    "version": "3.7.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

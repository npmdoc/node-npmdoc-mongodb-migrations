# npmdoc-mongodb-migrations

#### basic api documentation for  [mongodb-migrations (v0.8.5)](https://github.com/emirotin/mongodb-migrations)  [![npm package](https://img.shields.io/npm/v/npmdoc-mongodb-migrations.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mongodb-migrations) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mongodb-migrations.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mongodb-migrations)

#### A migration framework for MongoDB

[![NPM](https://nodei.co/npm/mongodb-migrations.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mongodb-migrations)

- [https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mongodb-migrations/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eugene Mirotin"
    },
    "bin": {
        "mm": "./bin/mm"
    },
    "bugs": {
        "url": "https://github.com/emirotin/mongodb-migrations/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.1",
        "lodash": "^4.13.0",
        "mkdirp": "^0.5.1",
        "mongodb": "^2.2.1",
        "nomnom": "^1.6.2"
    },
    "description": "A migration framework for MongoDB",
    "devDependencies": {
        "coffee-script": "~1.12.1",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-coffee": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "mocha": "^3.2.0",
        "rimraf": "^2.5.3",
        "should": "^11.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d027ef10fbb01f173735f00b74ba07dcf3cbb017",
        "tarball": "https://registry.npmjs.org/mongodb-migrations/-/mongodb-migrations-0.8.5.tgz"
    },
    "gitHead": "61f9c520f77f6cd6af73df75de6921dd1192bd85",
    "homepage": "https://github.com/emirotin/mongodb-migrations",
    "keywords": [
        "mongodb",
        "mongo",
        "migrate",
        "migration",
        "migrations"
    ],
    "license": "MIT",
    "main": "lib/mongodb-migrations.js",
    "maintainers": [
        {
            "name": "guard"
        }
    ],
    "name": "mongodb-migrations",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/emirotin/mongodb-migrations.git"
    },
    "scripts": {
        "build": "grunt",
        "dev": "grunt watch",
        "prepublish": "npm test && npm run build",
        "test": "mocha --compilers coffee:coffee-script/register -r should"
    },
    "version": "0.8.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

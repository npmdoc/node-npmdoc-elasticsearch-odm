# npmdoc-elasticsearch-odm

#### api documentation for  [elasticsearch-odm (v1.1.0)](https://github.com/zackiles/elasticsearch-odm#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-elasticsearch-odm.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-elasticsearch-odm) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-elasticsearch-odm.svg)](https://travis-ci.org/npmdoc/node-npmdoc-elasticsearch-odm)

#### Like Mongoose but for Elasticsearch. Define models, preform CRUD operations, and build advanced search queries.

[![NPM](https://nodei.co/npm/elasticsearch-odm.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elasticsearch-odm)

- [https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-elasticsearch-odm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Zachary Iles"
    },
    "bugs": {
        "url": "https://github.com/zackiles/elasticsearch-odm/issues"
    },
    "dependencies": {
        "bluebird": "~2.9.34",
        "dot-object": "^1.1.0",
        "elasticsearch": "~8.0.1",
        "kareem": "^1.0.1",
        "lodash": "~3.10.1",
        "pluralize": "~1.1.6",
        "winston": "~1.0.1"
    },
    "description": "Like Mongoose but for Elasticsearch. Define models, preform CRUD operations, and build advanced search queries.",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "mocha": "^2.3.0",
        "should": "^7.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "58596c6d6d5ef1fb8efb274464a04bd4e34dcf6c",
        "tarball": "https://registry.npmjs.org/elasticsearch-odm/-/elasticsearch-odm-1.1.0.tgz"
    },
    "gitHead": "8fee17214f56440e7ad768468c26d69184a670c4",
    "homepage": "https://github.com/zackiles/elasticsearch-odm#readme",
    "keywords": [
        "elasticsearch",
        "elastic",
        "odm",
        "orm",
        "database",
        "model",
        "query",
        "search",
        "driver",
        "client",
        "es",
        "promise",
        "bulk",
        "mapping"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "zacharyiles"
        }
    ],
    "name": "elasticsearch-odm",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zackiles/elasticsearch-odm.git"
    },
    "scripts": {
        "test": "NODE_ENV=test ./node_modules/.bin/mocha --check-leaks ./tests/**.js"
    },
    "version": "1.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

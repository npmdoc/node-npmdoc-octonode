# npmdoc-octonode

#### api documentation for  octonode (v0.7.11)  [![npm package](https://img.shields.io/npm/v/npmdoc-octonode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-octonode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-octonode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-octonode)

#### nodejs wrapper for github v3 api

[![NPM](https://nodei.co/npm/octonode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/octonode)

- [https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-octonode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-octonode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-octonode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-octonode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "octonode",
    "version": "0.7.11",
    "author": "Pavan Kumar Sunkara <pavan.sss1991@gmail.com> (http://pksunkara.github.com)",
    "description": "nodejs wrapper for github v3 api",
    "main": "./lib/octonode",
    "repository": "pksunkara/octonode",
    "keywords": [
        "wrapper",
        "api",
        "v3",
        "github"
    ],
    "scripts": {
        "test": "vows --spec $(find test -name '*.js')",
        "lib": "./node_modules/coffee-script/bin/cake lib",
        "watch": "./node_modules/coffee-script/bin/cake watch"
    },
    "dependencies": {
        "deep-extend": "^0.4.1",
        "randomstring": "^1.1.5",
        "request": "^2.72.0"
    },
    "devDependencies": {
        "coffee-script": "^1.12.4",
        "nock": "^8.0.0",
        "vows": "^0.8.1"
    },
    "engines": {
        "node": ">0.4.11"
    },
    "license": "MIT",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

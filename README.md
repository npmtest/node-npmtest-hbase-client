# npmtest-hbase-client

#### basic test coverage for  [hbase-client (v1.4.0)](http://github.com/alibaba/node-hbase-client)  [![npm package](https://img.shields.io/npm/v/npmtest-hbase-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hbase-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hbase-client.svg)](https://travis-ci.org/npmtest/node-npmtest-hbase-client)

#### Asynchronous HBase client for Node.js, pure javascript implementation.

[![NPM](https://nodei.co/npm/hbase-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hbase-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hbase-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hbase-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hbase-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hbase-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hbase-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hbase-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hbase-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hbase-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hbase-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hbase-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hbase-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hbase-client/build/test-report.html](https://npmtest.github.io/node-npmtest-hbase-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hbase-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hbase-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hbase-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hbase-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hbase-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hbase-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fengmk2",
        "url": "http://fengmk2.github.com"
    },
    "bugs": {
        "url": "https://github.com/alibaba/node-hbase-client/issues"
    },
    "config": {
        "blanket": {
            "pattern": "//^((?!(node_modules|test)).)*$/"
        },
        "travis-cov": {
            "threshold": 85
        }
    },
    "contributors": [
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "alsotang",
            "url": "https://github.com/alsotang"
        },
        {
            "name": "coolme200",
            "url": "https://github.com/coolme200"
        },
        {
            "name": "dead_horse",
            "url": "https://github.com/dead-horse"
        },
        {
            "name": "wision",
            "url": "https://github.com/wision"
        },
        {
            "name": "tzolkincz",
            "url": "https://github.com/tzolkincz"
        },
        {
            "name": "Takayuki Hasegawa",
            "url": "https://github.com/hase1031"
        }
    ],
    "dependencies": {
        "debug": "~1.0.4",
        "eventproxy": "~0.3.1",
        "long": "~1.1.5",
        "readable-stream": "1.1.11",
        "utility": "~0.1.16",
        "zookeeper-watcher": "~0.2.0"
    },
    "description": "Asynchronous HBase client for Node.js, pure javascript implementation.",
    "devDependencies": {
        "autod": "*",
        "benchmark": "*",
        "blanket": "*",
        "contributors": "*",
        "interceptor": "0.1.4",
        "istanbul": "~0.3.2",
        "jshint": "*",
        "mm": "~0.2.1",
        "mocha": "*",
        "moment": "*",
        "pedding": "~1.0.0",
        "should": "3"
    },
    "directories": {},
    "dist": {
        "shasum": "6a61a696fabbe553115c018551c2afa37deb393f",
        "tarball": "https://registry.npmjs.org/hbase-client/-/hbase-client-1.4.0.tgz"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "04463814fd89db6e972ce904d592ccd9ea16947a",
    "homepage": "http://github.com/alibaba/node-hbase-client",
    "keywords": [
        "node-hbase-client",
        "hbase",
        "hbase-client"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fengmk2"
        }
    ],
    "name": "hbase-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/alibaba/node-hbase-client.git"
    },
    "scripts": {
        "test": "make test-all"
    },
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-cluster-service

#### test coverage for  [cluster-service (v2.0.0)](https://github.com/godaddy/node-cluster-service)  [![npm package](https://img.shields.io/npm/v/npmtest-cluster-service.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cluster-service) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cluster-service.svg)](https://travis-ci.org/npmtest/node-npmtest-cluster-service)

#### Turns your single process code into a fault-resilient multi-process service with built-in REST & CLI support

[![NPM](https://nodei.co/npm/cluster-service.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cluster-service)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cluster-service/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cluster-service/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cluster-service/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cluster-service/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cluster-service/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cluster-service/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cluster-service/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cluster-service/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cluster-service/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cluster-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cluster-service/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cluster-service/build/test-report.html](https://npmtest.github.io/node-npmtest-cluster-service/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cluster-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cluster-service/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cluster-service/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cluster-service/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cluster-service/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cluster-service/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cluster-service/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cluster-service/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aaron Silvas"
    },
    "bin": {
        "cluster-service": "./bin/cservice",
        "cservice": "./bin/cservice",
        "cserviced": "./bin/cserviced"
    },
    "bugs": {
        "url": "https://github.com/godaddy/node-cluster-service/issues"
    },
    "dependencies": {
        "async": "~0.8.0",
        "colors": ">=0.6.2",
        "extend": ">=1.1.x",
        "optimist": ">=0.6.0"
    },
    "description": "Turns your single process code into a fault-resilient multi-process service with built-in REST & CLI support",
    "devDependencies": {
        "istanbul": "^0.3.13",
        "jshint": "^2.7.0",
        "mocha": "^2.2.4",
        "request": "^2.55.0",
        "sinon": "^1.14.1"
    },
    "directories": {},
    "dist": {
        "shasum": "313c2e239ffbfbf0ec2722bdd1bef3f02d7960cf",
        "tarball": "https://registry.npmjs.org/cluster-service/-/cluster-service-2.0.0.tgz"
    },
    "gitHead": "437862100152eb0346ad5ad8dcbc657499fb009c",
    "homepage": "https://github.com/godaddy/node-cluster-service",
    "keywords": [
        "cluster",
        "service",
        "ha",
        "high availability",
        "cli",
        "remote access",
        "multi process",
        "master",
        "child",
        "process",
        "monitor",
        "monitoring",
        "continous integration",
        "healthcheck",
        "heartbeat",
        "health check",
        "heart beat",
        "REST",
        "resilient"
    ],
    "license": "MIT",
    "main": "./cluster-service.js",
    "maintainers": [
        {
            "name": "asilvas"
        }
    ],
    "name": "cluster-service",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/godaddy/node-cluster-service.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha -- --ui bdd -R spec -t 5000 -d",
        "lint": "npm run-script lint-src && npm run-script lint-test",
        "lint-src": "jshint bin lib cluster-service.js",
        "lint-test": "jshint --config .test-jshintrc test",
        "start": "node scripts/start.js",
        "test": "npm run-script lint && npm run-script cover",
        "test-devel": "mocha bdd -R spec -t 5000 test/*.js test/workers/*.js"
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

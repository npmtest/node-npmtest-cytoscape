# npmtest-cytoscape

#### basic test coverage for  [cytoscape (v3.0.0)](http://js.cytoscape.org)  [![npm package](https://img.shields.io/npm/v/npmtest-cytoscape.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cytoscape) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cytoscape.svg)](https://travis-ci.org/npmtest/node-npmtest-cytoscape)

#### Graph theory (a.k.a. network) library for analysis and visualisation

[![NPM](https://nodei.co/npm/cytoscape.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cytoscape)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cytoscape/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cytoscape/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cytoscape/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cytoscape/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cytoscape/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cytoscape/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cytoscape/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cytoscape/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cytoscape/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cytoscape/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cytoscape/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cytoscape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cytoscape/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cytoscape/build/test-report.html](https://npmtest.github.io/node-npmtest-cytoscape/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cytoscape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cytoscape/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cytoscape/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cytoscape/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cytoscape/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cytoscape/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cytoscape/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cytoscape/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Max Franz",
        "url": "http://maxfranz.com"
    },
    "browser": {
        "child_process": false
    },
    "bugs": {
        "url": "https://github.com/cytoscape/cytoscape.js/issues"
    },
    "contributors": [
        {
            "name": "Christian Lopes"
        },
        {
            "name": "Yue Dong"
        },
        {
            "name": "Onur Sumer"
        },
        {
            "name": "Gerardo Huck"
        }
    ],
    "dependencies": {},
    "description": "Graph theory (a.k.a. network) library for analysis and visualisation",
    "devDependencies": {
        "benchmark": "^1.0.0",
        "bluebird": "^2.0.2",
        "browserify": "^13.0.0",
        "chai": "^1.9.0",
        "del": "^2.2.0",
        "gulp": "^3.9.1",
        "gulp-benchmark": "^1.1.1",
        "gulp-concat": "^2.6.0",
        "gulp-cssmin": "^0.1.4",
        "gulp-derequire": "^2.1.0",
        "gulp-download": "0.0.1",
        "gulp-eslint": "^3.0.1",
        "gulp-htmlmin": "^1.3.0",
        "gulp-inject": "^4.0.0",
        "gulp-livereload": "^3.8.1",
        "gulp-load-plugins": "^1.2.0",
        "gulp-mocha": "^2.2.0",
        "gulp-prompt": "^0.2.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-shell": "^0.5.2",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-uglify": "^1.5.3",
        "gulp-unzip": "^0.1.3",
        "gulp-util": "^3.0.7",
        "gulp-zip": "^3.2.0",
        "handlebars": "^4.0.5",
        "highlight.js": "^9.3.0",
        "jscs": "^2.11.0",
        "jsonlint": "^1.6.2",
        "marked": "^0.3.5",
        "mocha": "^2.3.2",
        "node-notifier": "^4.5.0",
        "run-sequence": "^1.1.5",
        "sniper": "^0.2.17",
        "vinyl-buffer": "^1.0.0",
        "vinyl-paths": "^2.1.0",
        "vinyl-source-stream": "^1.1.0",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d47ed5bd7fb0206325cd6343f7fd0e1be0d106b2",
        "tarball": "https://registry.npmjs.org/cytoscape/-/cytoscape-3.0.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "9be8ce6207433cc4bb32bf83485ae0805027bb14",
    "homepage": "http://js.cytoscape.org",
    "keywords": [
        "graph",
        "graph-theory",
        "network",
        "node",
        "edge",
        "vertex",
        "link",
        "analysis",
        "visualisation",
        "visualization",
        "requirejs",
        "amd",
        "commonjs",
        "node",
        "npm",
        "nodejs",
        "bower",
        "jquery",
        "biojs"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "cytoscape"
        },
        {
            "name": "maxkfranz"
        }
    ],
    "name": "cytoscape",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cytoscape/cytoscape.js.git"
    },
    "scripts": {
        "sniper": "sniper .",
        "test": "gulp test && gulp test-browserify"
    },
    "sniper": {
        "js": [
            "http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js",
            "/build/cytoscape.js"
        ],
        "first": "images"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

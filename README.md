# npmtest-svg-injector

#### basic test coverage for  [svg-injector (v1.1.3)](https://github.com/iconic/SVGInjector)  [![npm package](https://img.shields.io/npm/v/npmtest-svg-injector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-svg-injector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-svg-injector.svg)](https://travis-ci.org/npmtest/node-npmtest-svg-injector)

#### Fast, caching, dynamic inline SVG DOM injection library

[![NPM](https://nodei.co/npm/svg-injector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/svg-injector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-svg-injector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-injector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-svg-injector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-svg-injector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-svg-injector/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-svg-injector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-svg-injector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-svg-injector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-svg-injector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-svg-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-svg-injector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-svg-injector/build/test-report.html](https://npmtest.github.io/node-npmtest-svg-injector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-svg-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-svg-injector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-svg-injector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-svg-injector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-svg-injector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-svg-injector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-svg-injector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-svg-injector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Iconic",
        "url": "https://useiconic.com/"
    },
    "bugs": {
        "url": "https://github.com/iconic/SVGInjector/issues"
    },
    "dependencies": {},
    "description": "Fast, caching, dynamic inline SVG DOM injection library",
    "devDependencies": {
        "github-changes": "0.0.11",
        "jshint": "^2.5.0",
        "uglify-js": "^2.4.13"
    },
    "directories": {},
    "dist": {
        "shasum": "8fba18d7419e5f818e712c4f82d83ee357610e61",
        "tarball": "https://registry.npmjs.org/svg-injector/-/svg-injector-1.1.3.tgz"
    },
    "gitHead": "bd355bebb1903e1eac608883a8b5af5e7e6d5fd2",
    "homepage": "https://github.com/iconic/SVGInjector",
    "keywords": [
        "SVG",
        "Scalable Vector Graphics",
        "SVG injector",
        "images",
        "img",
        "html",
        "DOM"
    ],
    "license": "MIT",
    "main": "svg-injector.js",
    "maintainers": [
        {
            "name": "iconic"
        }
    ],
    "name": "svg-injector",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/iconic/SVGInjector.git"
    },
    "scripts": {
        "build": "uglifyjs ./svg-injector.js --stats --compress --mangle --comments --output ./svg-injector.min.js --source-map svg-injector.map.js && mv -f svg-injector.{map,min}.js ./dist",
        "changelog": "github-changes -o iconic -r SVGInjector --use-commit-body",
        "changelog-post": "git add CHANGELOG.md && git commit -m 'Updated CHANGELOG'",
        "release": "for TASK in (test build changelog changelog-post tag); do npm run $TASK; done",
        "tag": "git tag ${npm_package_version} && git push --tags",
        "test": "jshint svg-injector.js",
        "test-version": "bash -c 'echo $npm_package_version'"
    },
    "version": "1.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

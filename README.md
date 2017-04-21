# npmtest-postcss-modules

#### basic test coverage for  [postcss-modules (v0.6.4)](https://github.com/css-modules/postcss-modules#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-postcss-modules.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-postcss-modules) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-postcss-modules.svg)](https://travis-ci.org/npmtest/node-npmtest-postcss-modules)

#### PostCSS plugin to use CSS Modules everywhere

[![NPM](https://nodei.co/npm/postcss-modules.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/postcss-modules)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-postcss-modules/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-modules/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-modules/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-postcss-modules/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-postcss-modules/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-postcss-modules/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-postcss-modules/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-postcss-modules/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-postcss-modules/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-postcss-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-postcss-modules/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-postcss-modules/build/test-report.html](https://npmtest.github.io/node-npmtest-postcss-modules/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-postcss-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-postcss-modules/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-postcss-modules/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-postcss-modules/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-postcss-modules/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexander Madyankin"
    },
    "bugs": {
        "url": "https://github.com/css-modules/postcss-modules/issues"
    },
    "dependencies": {
        "css-modules-loader-core": "^1.0.1",
        "generic-names": "^1.0.2",
        "postcss": "^5.2.8",
        "string-hash": "^1.1.1"
    },
    "description": "PostCSS plugin to use CSS Modules everywhere",
    "devDependencies": {
        "autoprefixer": "^6.6.0",
        "ava": "^0.17.0",
        "babel": "^6.5.2",
        "babel-cli": "^6.18.0",
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.1.1",
        "babel-preset-es2015": "^6.18.0",
        "eslint": "^3.12.2",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-import": "^2.2.0",
        "file-exists": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "77a58bb77ba1b4392b270c0b59852fd75e89a8b4",
        "tarball": "https://registry.npmjs.org/postcss-modules/-/postcss-modules-0.6.4.tgz"
    },
    "gitHead": "7d108142860d95ec36c5c94b7253c5ba19ab6434",
    "homepage": "https://github.com/css-modules/postcss-modules#readme",
    "keywords": [
        "postcss",
        "css",
        "postcss-plugin",
        "modules",
        "css modules",
        "components"
    ],
    "license": "MIT",
    "main": "build/index.js",
    "maintainers": [
        {
            "name": "outpunk"
        }
    ],
    "name": "postcss-modules",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/css-modules/postcss-modules.git"
    },
    "require": "babel-core/register",
    "scripts": {
        "postpublish": "rm -rf build && git push --follow-tags",
        "prepublish": "npm run transpile",
        "pretest": "$(npm bin)/eslint src test",
        "test": "$(npm bin)/babel-node $(npm bin)/ava",
        "transpile": "$(npm bin)/babel src -d build"
    },
    "version": "0.6.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

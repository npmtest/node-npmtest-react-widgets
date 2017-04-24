# npmtest-react-widgets

#### basic test coverage for  [react-widgets (v3.4.6)](http://jquense.github.io/react-widgets/docs/)  [![npm package](https://img.shields.io/npm/v/npmtest-react-widgets.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-widgets) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-widgets.svg)](https://travis-ci.org/npmtest/node-npmtest-react-widgets)

#### An à la carte set of polished, extensible, and accessible inputs built for React

[![NPM](https://nodei.co/npm/react-widgets.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-widgets)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-widgets/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-widgets/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-widgets/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-widgets/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-widgets/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-widgets/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-widgets/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-widgets/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-widgets/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-widgets/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-widgets/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-widgets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-widgets/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-widgets/build/test-report.html](https://npmtest.github.io/node-npmtest-react-widgets/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-widgets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-widgets/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-widgets/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-widgets/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-widgets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-widgets/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-widgets/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-widgets/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason"
    },
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/jquense/react-widgets/issues"
    },
    "dependencies": {
        "classnames": "^2.1.2",
        "date-arithmetic": "^3.0.0",
        "deconstruct-number-format": "0.0.1",
        "dom-helpers": "^2.2.4",
        "format-number-with-string": "0.0.2",
        "invariant": "^2.1.0",
        "loose-envify": "^1.2.0",
        "uncontrollable": "^4.0.0",
        "warning": "^2.0.0"
    },
    "description": "An à la carte set of polished, extensible, and accessible inputs built for React",
    "devDependencies": {
        "@monastic.panic/component-playground": "^2.0.0",
        "babel-cli": "^6.7.5",
        "babel-core": "^6.7.6",
        "babel-eslint": "^6.0.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-jason": "^1.0.1",
        "bill": "^3.2.2",
        "chance": "^1.0.1",
        "cpy-cli": "^1.0.0",
        "css-loader": "^0.23.1",
        "es5-shim": "^4.4.1",
        "eslint": "^1.10.3",
        "eslint-plugin-mocha": "^1.1.0",
        "eslint-plugin-react": "^4.3.0",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.8.1",
        "glob": "^7.0.5",
        "globalize": "^0.1.x",
        "imports-loader": "^0.6.4",
        "json-loader": "^0.5.3",
        "karma": "^0.13.3",
        "karma-chrome-launcher": "^0.2.1",
        "karma-expect": "~1.1.0",
        "karma-jsdom-launcher": "^3.0.0",
        "karma-mocha": "^0.2.0",
        "karma-mocha-reporter": "^2.0.0",
        "karma-sauce-launcher": "^0.3.1",
        "karma-sinon": "^1.0.4",
        "karma-sourcemap-loader": "^0.3.5",
        "karma-webpack": "^1.7.0",
        "less": "^2.5.1",
        "less-loader": "^2.2.0",
        "less2sass": "^1.0.2",
        "marked": "^0.3.5",
        "mkdirp": "^0.5.1",
        "mocha": "^2.3.4",
        "moment": "^2.10.6",
        "mt-changelog": "^0.6.2",
        "node-libs-browser": "^1.0.0",
        "output-file-sync": "^1.1.1",
        "prismjs": "^1.2.0",
        "raw-loader": "^0.5.1",
        "react": "^15.2.0",
        "react-bootstrap": "^0.29.0-0",
        "react-dom": "^15.2.0",
        "react-router": "2.0.1",
        "release-script": "^1.0.2",
        "rimraf": "^2.4.2",
        "scriptjs": "^2.5.8",
        "sinon": "^1.17.2",
        "style-loader": "^0.13.1",
        "teaspoon": "^6.4.1",
        "url-loader": "^0.5.5",
        "webpack": "^1.10.5",
        "webpack-dev-server": "^1.10.1",
        "yargs": "^4.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e67829ffd358be9bf8e9eac17dbe08377c89f8e5",
        "tarball": "https://registry.npmjs.org/react-widgets/-/react-widgets-3.4.6.tgz"
    },
    "gitHead": "d2abdc451a1ea2fdb7c63568d2b3a5c35353f07a",
    "homepage": "http://jquense.github.io/react-widgets/docs/",
    "keywords": [
        "react",
        "widgets",
        "dropdown",
        "combobox",
        "calendar",
        "datepicker",
        "date picker",
        "numberpicker",
        "number picker",
        "radio group",
        "checkbox list",
        "multiselect",
        "form",
        "input",
        "react-ui",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "monastic.panic"
        }
    ],
    "name": "react-widgets",
    "optionalDependencies": {
        "deconstruct-number-format": "0.0.1",
        "format-number-with-string": "0.0.2"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jquense/react-widgets.git"
    },
    "scripts": {
        "alpha": "release --preid alpha --tag next",
        "assets:dist": "cpy src/img/* dist/img/ && cpy src/fonts/* dist/fonts/",
        "assets:lib": "cpy src/img/* lib/img/ && cpy src/fonts/* lib/fonts/",
        "beta": "release --preid beta --tag next",
        "build": "npm run build:lib && npm run build:dist",
        "build:dist": "npm run clean:dist && npm run compile:dist & npm run compile:locale && npm run less && npm run assets:dist",
        "build:docs": "npm run clean:docs && npm run compile:docs",
        "build:lib": "npm run clean:lib && npm run compile:lib && npm run styles && npm run assets:lib",
        "clean:dist": "rimraf ./dist/*",
        "clean:docs": "rimraf ./docs/public/*",
        "clean:lib": "rimraf ./lib/*",
        "compile:dist": "webpack --config build/browser.config.js",
        "compile:docs": "webpack --config build/docs.config.js --production",
        "compile:lib": "babel src --out-dir lib",
        "compile:locale": "webpack --config build/localizers.config.js",
        "dev": "webpack-dev-server --config ./build/dev.config.js --hot",
        "docs": "npm run clean:docs && webpack-dev-server --config ./build/docs.config.js --hot",
        "less": "lessc -x src/less/react-widgets.less dist/css/react-widgets.css",
        "lint": "eslint src test --ext .jsx --ext .js",
        "release": "release",
        "styles": "cpy src/less/* lib/less/ && npm run to-sass",
        "tdd": "karma start",
        "test": "npm run lint && npm run test:all",
        "test:all": "mocha -R spec ./test/server.js && karma start karma.conf.js --single-run=true",
        "to-sass": "node ./build/lessToSass.js"
    },
    "version": "3.4.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

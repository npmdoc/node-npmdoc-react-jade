# npmdoc-react-jade

#### api documentation for  react-jade (v2.5.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-jade.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-jade) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-jade.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-jade)

#### Compile Jade to React JavaScript

[![NPM](https://nodei.co/npm/react-jade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-jade)

- [https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-jade/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-jade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-jade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-jade",
    "version": "2.5.0",
    "description": "Compile Jade to React JavaScript",
    "keywords": [],
    "dependencies": {
        "acorn": "^1.1.0",
        "constantinople": "^3.0.1",
        "ent": "^2.2.0",
        "jade": "1.9.2",
        "js-stringify": "^1.0.1",
        "resolve": "^1.1.6",
        "static-module": "^1.1.2",
        "uglify-js": "^2.4.21",
        "with": "^5.0.0"
    },
    "devDependencies": {
        "es6ify": "^1.6.0",
        "gethub": "^2.0.1",
        "htmlparser2": "^3.8.2",
        "istanbul": "^0.3.14",
        "marked": "^0.3.3",
        "react": "^0.14.0",
        "react-dom": "^0.14.0",
        "rimraf": "^2.3.3",
        "testit": "^2.0.2",
        "unescape-html": "^1.0.0"
    },
    "peerDependencies": {
        "react": ">=0.12.0 <0.15.0"
    },
    "scripts": {
        "test": "node test/download-jade-tests.js && node test/index.js && npm run coverage",
        "coverage": "istanbul cover test"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/jadejs/react-jade.git"
    },
    "author": "ForbesLindesay",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

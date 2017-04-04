# api documentation for  [gulp-svgmin (v1.2.3)](https://github.com/ben-eb/gulp-svgmin)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-svgmin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-svgmin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-svgmin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-svgmin)
#### Minify SVG files with gulp.

[![NPM](https://nodei.co/npm/gulp-svgmin.png?downloads=true)](https://www.npmjs.com/package/gulp-svgmin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-svgmin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-svgmin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Briggs",
        "email": "beneb.info@gmail.com",
        "url": "http://beneb.info"
    },
    "ava": {
        "require": "babel-register"
    },
    "bugs": {
        "url": "https://github.com/ben-eb/gulp-svgmin/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.4",
        "svgo": "^0.7.0"
    },
    "description": "Minify SVG files with gulp.",
    "devDependencies": {
        "ava": "^0.16.0",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.2",
        "babel-plugin-add-module-exports": "^0.2.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-es2015-loose": "^7.0.0",
        "babel-preset-stage-0": "^6.5.0",
        "babel-register": "^6.9.0",
        "chai": "~3.5.0",
        "coveralls": "^2.11.6",
        "del-cli": "^0.2.0",
        "eslint": "^3.0.0",
        "eslint-config-cssnano": "^3.0.0",
        "eslint-plugin-babel": "^3.3.0",
        "eslint-plugin-import": "^1.10.2",
        "nyc": "^8.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "88947b132e15b2de43d1dbccb30455319c5e50b5",
        "tarball": "https://registry.npmjs.org/gulp-svgmin/-/gulp-svgmin-1.2.3.tgz"
    },
    "eslintConfig": {
        "extends": "cssnano"
    },
    "files": [
        "LICENSE-MIT",
        "dist"
    ],
    "gitHead": "d0386b8a268328e44f4dd121216351675bb58f70",
    "homepage": "https://github.com/ben-eb/gulp-svgmin",
    "keywords": [
        "gulpplugin",
        "minify",
        "svg",
        "svgo"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "beneb",
            "email": "therealbenbriggs@hotmail.com"
        }
    ],
    "name": "gulp-svgmin",
    "nyc": {
        "exclude": [
            "node_modules",
            "**/__tests__"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ben-eb/gulp-svgmin.git"
    },
    "scripts": {
        "prepublish": "del-cli dist && BABEL_ENV=publish babel src --out-dir dist --ignore /__tests__/",
        "pretest": "eslint src",
        "test": "nyc ava src/__tests__",
        "test-012": "nyc ava src/__tests__"
    },
    "version": "1.2.3"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-svgmin](#apidoc.module.gulp-svgmin)



# <a name="apidoc.module.gulp-svgmin"></a>[module gulp-svgmin](#apidoc.module.gulp-svgmin)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# api documentation for  [country-data (v0.0.31)](https://github.com/OpenBookPrices/country-data)  [![npm package](https://img.shields.io/npm/v/npmdoc-country-data.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-country-data) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-country-data.svg)](https://travis-ci.org/npmdoc/node-npmdoc-country-data)
#### Data about countries - like their ISO codes and currencies

[![NPM](https://nodei.co/npm/country-data.png?downloads=true)](https://www.npmjs.com/package/country-data)

[![apidoc](https://npmdoc.github.io/node-npmdoc-country-data/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-country-data_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-country-data/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-country-data/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-country-data/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Edmund von der Burg"
    },
    "bugs": {
        "url": "https://github.com/OpenBookPrices/country-data/issues"
    },
    "dependencies": {
        "currency-symbol-map": "~2",
        "underscore": ">1.4.4"
    },
    "description": "Data about countries - like their ISO codes and currencies",
    "devDependencies": {
        "canonical-json": "~0.0.4",
        "chai": ">1.8.1",
        "csv": "~0.4",
        "mocha": "~2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "80966b8e1d147fa6d6a589d32933f8793774956d",
        "tarball": "https://registry.npmjs.org/country-data/-/country-data-0.0.31.tgz"
    },
    "gitHead": "011dbb6658b0df5a36690af7086baa3e5c20c30c",
    "homepage": "https://github.com/OpenBookPrices/country-data",
    "keywords": [
        "data",
        "country"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "evdb",
            "email": "evdb@ecclestoad.co.uk"
        },
        {
            "name": "niftylettuce",
            "email": "niftylettuce@gmail.com"
        }
    ],
    "name": "country-data",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/OpenBookPrices/country-data.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.0.31"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module country-data](#apidoc.module.country-data)
1.  object <span class="apidocSignatureSpan">country-data.</span>callingCodes
1.  object <span class="apidocSignatureSpan">country-data.</span>callingCountries
1.  object <span class="apidocSignatureSpan">country-data.</span>continents
1.  object <span class="apidocSignatureSpan">country-data.</span>countries
1.  object <span class="apidocSignatureSpan">country-data.</span>currencies
1.  object <span class="apidocSignatureSpan">country-data.</span>languages
1.  object <span class="apidocSignatureSpan">country-data.</span>lookup
1.  object <span class="apidocSignatureSpan">country-data.</span>regions

#### [module country-data.lookup](#apidoc.module.country-data.lookup)
1.  [function <span class="apidocSignatureSpan">country-data.lookup.</span>countries ()](#apidoc.element.country-data.lookup.countries)
1.  [function <span class="apidocSignatureSpan">country-data.lookup.</span>currencies ()](#apidoc.element.country-data.lookup.currencies)
1.  [function <span class="apidocSignatureSpan">country-data.lookup.</span>languages ()](#apidoc.element.country-data.lookup.languages)



# <a name="apidoc.module.country-data"></a>[module country-data](#apidoc.module.country-data)



# <a name="apidoc.module.country-data.lookup"></a>[module country-data.lookup](#apidoc.module.country-data.lookup)

#### <a name="apidoc.element.country-data.lookup.countries"></a>[function <span class="apidocSignatureSpan">country-data.lookup.</span>countries ()](#apidoc.element.country-data.lookup.countries)
- description and source-code
```javascript
countries = function () { [native code] }
```
- example usage
```shell
...
console.log( regions.europe.countries )
'''

''' javascript
var lookup = require('country-data').lookup;

// Match a value (grab first from array)
var france = lookup.countries({name: 'France'})[0];

// Or match one of several possible values.
var eurozone_countries = lookup.countries({currencies: 'EUR'});
'''

It is very simple for now - feel free to contribute more helpful accessors.
...
```

#### <a name="apidoc.element.country-data.lookup.currencies"></a>[function <span class="apidocSignatureSpan">country-data.lookup.</span>currencies ()](#apidoc.element.country-data.lookup.currencies)
- description and source-code
```javascript
currencies = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.country-data.lookup.languages"></a>[function <span class="apidocSignatureSpan">country-data.lookup.</span>languages ()](#apidoc.element.country-data.lookup.languages)
- description and source-code
```javascript
languages = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

# npmtest-npm-collection-language-tools

#### basic test coverage for  [npm-collection-language-tools (v1.9.0)](https://github.com/zeke/npm-collection-language-tools)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-collection-language-tools.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-collection-language-tools) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-collection-language-tools.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-collection-language-tools)

#### A collection of npm modules for working with words and language

[![NPM](https://nodei.co/npm/npm-collection-language-tools.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-collection-language-tools)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-collection-language-tools/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-collection-language-tools/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-collection-language-tools/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-collection-language-tools/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-collection-language-tools/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-collection-language-tools/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-collection-language-tools/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-collection-language-tools",
    "version": "1.9.0",
    "description": "A collection of npm modules for working with words and language",
    "main": "index.js",
    "dependencies": {
        "adverb-where": "0.0.7",
        "afinn-111": "^0.1.5",
        "afinn-96": "^0.1.4",
        "alex": "^1.2.0",
        "alphabet": "^1.0.0",
        "an-array-of-english-words": "^1.0.0",
        "buzzwords": "^1.0.1",
        "cat-names": "^1.0.2",
        "clj-fuzzy": "^0.2.1",
        "cmu-pronouncing-dictionary": "^1.0.1",
        "dice-coefficient": "^0.1.4",
        "did-you-mean": "0.0.1",
        "dog-names": "^1.0.2",
        "double-metaphone": "^0.1.4",
        "fillers": "^1.0.0",
        "franc": "^1.1.1",
        "hedges": "^1.0.0",
        "inflection": "^1.6.0",
        "irregular-plurals": "^1.1.0",
        "jaro-winkler": "^0.2.6",
        "leven": "^1.0.1",
        "levenmorpher": "^1.1.0",
        "levenshtein-edit-distance": "^1.0.0",
        "lunr": "^0.5.7",
        "metaphone": "^1.0.1",
        "moby": "^1.1.1",
        "name-that-color": "^0.1.0",
        "no-cliches": "^0.1.0",
        "npm-synonym": "^1.1.1",
        "ord.zeke.xxx": "^1.0.0",
        "passive-voice": "^0.1.0",
        "profanities": "^1.0.1",
        "retext": "^1.0.0",
        "sentiment": "^1.0.2",
        "soundex-code": "^0.1.2",
        "stemmer": "^0.1.4",
        "superb": "^1.1.3",
        "superheroes": "^1.0.0",
        "supervillains": "^1.0.0",
        "syllable": "^0.1.4",
        "too-wordy": "^0.1.3",
        "weasel-words": "^0.1.1",
        "weasels": "^1.0.0",
        "wikipedia-translator": "^1.1.0",
        "word-list": "^1.0.0",
        "write-good": "^0.9.1"
    },
    "devDependencies": {},
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/zeke/npm-collection-language-tools.git"
    },
    "keywords": [
        "language",
        "words",
        "collection"
    ],
    "author": "Zeke Sikelianos <zeke@sikelianos.com> (http://zeke.sikelianos.com/)",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/zeke/npm-collection-language-tools/issues"
    },
    "homepage": "https://github.com/zeke/npm-collection-language-tools",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

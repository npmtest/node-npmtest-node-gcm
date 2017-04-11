# test coverage for  [node-gcm (v0.14.5)](https://github.com/ToothlessGear/node-gcm)  [![npm package](https://img.shields.io/npm/v/npmtest-node-gcm.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-gcm) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-gcm.svg)](https://travis-ci.org/npmtest/node-npmtest-node-gcm)
#### Easy interface for Google's Cloud Messaging service (now Firebase Cloud Messaging)

[![NPM](https://nodei.co/npm/node-gcm.png?downloads=true)](https://www.npmjs.com/package/node-gcm)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-gcm/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gcm/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-gcm/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-gcm/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-gcm/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-gcm/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-gcm/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-gcm/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-node-gcm/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-gcm/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-node-gcm%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-gcm/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-gcm/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-node-gcm%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-gcm/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-gcm/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-gcm/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marcus Farkas",
        "email": "toothlessgear@finitebox.com"
    },
    "bugs": {
        "url": "https://github.com/ToothlessGear/node-gcm/issues"
    },
    "contributors": [
        {
            "name": "Marcus Farkas",
            "email": "toothlessgear@finitebox.com"
        },
        {
            "name": "monkbroc",
            "email": "jvanier@gmail.com",
            "url": "https://github.com/monkbroc"
        },
        {
            "name": "zlyinfinite",
            "url": "https://github.com/zlyinfinite"
        },
        {
            "name": "Yann Biancheri",
            "email": "yann.biancheri@gmail.com",
            "url": "https://github.com/yannooo"
        },
        {
            "name": "Hamid Palo",
            "email": "hamid@fogcreek.com",
            "url": "https://github.com/hamidp"
        },
        {
            "name": "Dotan J. Nahum",
            "email": "jondotan@gmail.com",
            "url": "https://github.com/jondot"
        },
        {
            "name": "Max Rabin",
            "email": "rabin.max@gmail.com",
            "url": "https://github.com/maxrabin"
        },
        {
            "name": "Olivier Poitrey",
            "email": "rs@dailymotion.com",
            "url": "https://github.com/rs"
        },
        {
            "name": "George Miroshnykov",
            "email": "george.miroshnykov@gmail.com",
            "url": "https://github.com/laggyluke"
        },
        {
            "name": "Alejandro Garcia Gil",
            "email": "alejandro@ideaknow.com",
            "url": "https://github.com/Alegege"
        },
        {
            "name": "Ismael Gorissen",
            "email": "ismael.gorissen@gmail.com",
            "url": "https://github.com/igorissen"
        },
        {
            "name": "Joris Verbogt",
            "email": "joris@notifica.re",
            "url": "https://github.com/silentjohnny"
        },
        {
            "name": "goelvivek",
            "email": "goelvivek2011@gmail.com",
            "url": "https://github.com/goelvivek"
        },
        {
            "name": "Lars Jacob",
            "email": "lars@jaclar.net",
            "url": "https://github.com/jaclar"
        },
        {
            "name": "Roman Iakovlev",
            "email": "roman.iakovlev@here.com",
            "url": "https://github.com/RomanIakovlev"
        },
        {
            "name": "Roman Skvazh",
            "email": "roman.skvazh@gmail.com",
            "url": "https://github.com/rskvazh"
        },
        {
            "name": "Jeremy Goldstein",
            "email": "jg-dev@live.com",
            "url": "https://github.com/jg10"
        },
        {
            "name": "Adam Patacchiola",
            "email": "adam@2fours.com",
            "url": "https://github.com/surespot"
        },
        {
            "name": "Ivan Longin",
            "email": "ivan.longin@infobip.com",
            "url": "https://github.com/ilongin"
        },
        {
            "name": "Paul Bininda",
            "email": "paul@bininda.com",
            "url": "https://github.com/pbininda"
        },
        {
            "name": "Matt Merkes",
            "email": "matt.merkes@gmail.com"
        },
        {
            "name": "Niels Roesen Abildgaard",
            "email": "niels.abildgaard@gmail.com",
            "url": "https://github.com/hypesystem"
        },
        {
            "name": "Nonemoticoner",
            "email": "nonemoticoner@gmail.com",
            "url": "https://github.com/Nonemoticoner"
        },
        {
            "name": "Simen Bekkhus",
            "email": "sbekkhus91@gmail.com",
            "url": "https://github.com/SimenB"
        },
        {
            "name": "Alexander Johansson",
            "email": "alex@dice.fm",
            "url": "https://github.com/KATT"
        },
        {
            "name": "Ashwin R",
            "email": "ashrko619@gmail.com",
            "url": "https://github.com/ashrko619"
        },
        {
            "name": "Kaija Chang",
            "email": "kaija.chang@gmail.com",
            "url": "https://github.com/kaija"
        },
        {
            "name": "Mo Kamioner",
            "email": "mkamioner@gmail.com",
            "url": "https://github.com/mkamioner"
        },
        {
            "name": "Bastien Léonard",
            "email": "bastien.leonard@gmail.com",
            "url": "https://github.com/bastienleonard"
        },
        {
            "name": "Elad Nava",
            "email": "eladnava@gmail.com",
            "url": "https://github.com/eladnava"
        },
        {
            "name": "Marc Obrador",
            "email": "marcobrador89@gmail.com",
            "url": "https://github.com/marcobrador"
        },
        {
            "name": "Chirag Choudhary",
            "email": "chirag200666@gmail.com",
            "url": "https://github.com/chirag200666"
        },
        {
            "name": "Alexander Amin",
            "email": "alexander.amin@high5-it.de",
            "url": "https://github.com/AlexAmin"
        },
        {
            "name": "Gaurav Nolkha",
            "email": "gaurav@swiftday.com",
            "url": "https://github.com/vibgy"
        }
    ],
    "dependencies": {
        "debug": "^0.8.1",
        "lodash": "^3.10.1",
        "request": "^2.81.0"
    },
    "description": "Easy interface for Google's Cloud Messaging service (now Firebase Cloud Messaging)",
    "devDependencies": {
        "chai": "^2.2.0",
        "mocha": "^2.2.4",
        "proxyquire": "^1.4.0",
        "sinon": "^1.14.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "37cc5b364c6e4458b610ffad603eb05d620b9eb5",
        "tarball": "https://registry.npmjs.org/node-gcm/-/node-gcm-0.14.5.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "files": [
        "index.js",
        "lib/"
    ],
    "gitHead": "ef76cce1c197f4b7ee4360707f77e9afc9d537a1",
    "homepage": "https://github.com/ToothlessGear/node-gcm",
    "keywords": [
        "google",
        "cloud",
        "push",
        "notifications",
        "android",
        "c2dm",
        "gcm",
        "fcm",
        "firebase",
        "ios",
        "apn",
        "messaging"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "eladnava",
            "email": "eladnava@gmail.com"
        },
        {
            "name": "hypesystem",
            "email": "niels.abildgaard@gmail.com"
        },
        {
            "name": "toothlessgear",
            "email": "toothlessgear@finitebox.com"
        }
    ],
    "name": "node-gcm",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ToothlessGear/node-gcm.git",
        "web": "http://github.com/ToothlessGear/node-gcm"
    },
    "scripts": {
        "test": "mocha test/**/*Spec.js"
    },
    "version": "0.14.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)

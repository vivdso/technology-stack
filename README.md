# Technology Stack [![Join the chat at https://gitter.im/dwyl/chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/chat/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This document describes the full technology stack we are using in dwyl.

If you have ***any questions*** please
[***ask***](https://github.com/dwyl/technology-stack/issues)

## Overview

This diagram is meant to give complete beginners an overview of our stack:

![dwyl-stack-lighter-blue](https://cloud.githubusercontent.com/assets/194400/9354261/e971fe58-4666-11e5-848f-67dc11d41bfb.jpg)

Each of these components will be described in detail below:

## Open Source Modules We Use

### For Us By Us

We ***craft code*** to ***scratch our own itch*** and ***everything*** we do is ***always Open Source***

| Project | Use Case | Build | Coverage | Dependencies | Learn |
| --------|----------|:-----:|:--------:|
| **[hapi-auth-jwt2]** | Authorization | [![build][jwt2-bi]][jwt2] | [![cov][jwt2-dep]][jwt2] | [![deps][jwt2-dep]][jwt2] | [learn-jwt] |
| **[env2]** | Environment Variables | [![build][env2-bi]][env2] | [![cov][env2-dep]][env2] | [![deps][env2-dep]][env2] | [learn-env2] |
| **[esta]** | ElasticSearch | [![build][env2-bi]][env2] | [![cov][env2-dep]][env2] | [![deps][env2-dep]][env2] | [learn-elasticsearch] |

### External <small>(*projects built by people we trust*)</small>

+ **Node.js** - the most popular JavaScript runtime for easily building fast,
scalable network applications. Lightweight and efficient, perfect for
data-intensive real-time apps. http://nodejs.org/
+ **Hapi.js** - A rich framework for building applications and services.
https://github.com/nelsonic/learn-hapi

<br />
<br />
## tl;dr

Example Image Link Markdown:
```sh
[![Node.js Version][node-version-image]][node-version-url]
[node-version-image]: https://img.shields.io/node/v/listdirs.svg?style=flat
[node-version-url]: http://nodejs.org/download/
```

[hapi-auth-jwt2]: https://github.com/dwyl/hapi-auth-jwt2
[jwt2-bi]: https://travis-ci.org/dwyl/hapi-auth-jwt2.svg?branch=master
[jwt2-cc]: https://codeclimate.com/github/dwyl/hapi-auth-jwt2/badges/coverage.svg
[jwt2-dep]: https://david-dm.org/dwyl/hapi-auth-jwt2.svg
[learn-jwt]: https://github.com/dwyl/learn-json-web-tokens
[jwt2]: https://github.com/dwyl/hapi-auth-jwt2

[env2]: https://github.com/dwyl/env2
[env2-bi]: https://travis-ci.org/dwyl/env2.svg?branch=master
[env2-cc]: https://codeclimate.com/github/dwyl/env2/badges/coverage.svg
[env2-dep]: https://david-dm.org/dwyl/env2.svg
[learn-env2]: https://github.com/dwyl/env2#what

[esta]: https://github.com/dwyl/esta
[env2-bi]: https://travis-ci.org/dwyl/esta.svg?branch=master
[env2-cc]: https://codeclimate.com/github/dwyl/eta/badges/coverage.svg
[env2-dep]: https://david-dm.org/dwyl/esta.svg
[learn-elasticsearch]: https://github.com/dwyl/learn-elasticsearch

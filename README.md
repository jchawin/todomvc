# Nuxt.js TodoMVC Example

> Nuxt.js is a framework for building Universal Vue.js Applications.

> _[Nuxt.js - nuxtjs.org](https://nuxtjs.org)_

## Setup

```bash
# install dependencies
npm install # or yarn

# serve in dev mode, with hot reload at localhost:3000
npm run dev

# build for production
npm run build

# serve in production mode
npm start
```

## Learning Nuxt.js

The [Nuxt.js website](https://nuxtjs.org/) is a great resource to get started.

Here are some links you may find helpful:

* [Official Guide](https://nuxtjs.org/guide)
* [API Reference](https://nuxtjs.org/api)
* [Examples](https://nuxtjs.org/examples)

Get help from other Vue.js users:

* [Nuxt.js on Twitter](https://twitter.com/nuxt_js)
* [Nuxt.js on Gitter](https://gitter.im/nuxt/nuxt.js)

## Add Newrelic
```bash
# install newrelic on project
npm i newrelic

# copy file newrelic to root project
cp node_modules/newrelic/newrelic.js .

# edit file newrelic set value for app_name and licence_key
nano newrelic.js
```

import newrelic to project go to start file and add this code on top code line.

const nr = require('newrelic')

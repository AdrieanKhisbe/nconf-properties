NConf Properties
================
[![Version npm](https://img.shields.io/npm/v/nconf-properties.svg)](https://www.npmjs.com/package/nconf-properties)
[![Build Status](https://img.shields.io/travis/AdrieanKhisbe/nconf-properties/master.svg)](https://travis-ci.org/AdrieanKhisbe/nconf-properties)
[![Dependencies](https://img.shields.io/david/AdrieanKhisbe/nconf-properties.svg)](https://david-dm.org/AdrieanKhisbe/nconf-properties)

> Properties format plugins for [nconf](https://www.npmjs.org/package/nconf)

## Usage

```js
const nconf = require('nconf');

nconf.file({
  file: '/path/to/some/file.properties',
  format: require('nconf-properties')
});
```

## Install

```bash
npm install nconf nconf-properties
```

## License

MIT

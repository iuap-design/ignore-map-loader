# ignore-map-loader
Ignore. map files in webpack

[![npm version](https://img.shields.io/npm/v/ignore-map-loader.svg)](https://www.npmjs.com/package/ignore-map-loader)
[![NPM downloads](http://img.shields.io/npm/dt/ignore-map-loader.svg?style=flat)](https://npmjs.org/package/ignore-map-loader)

## Getting Started

To begin, you'll need to install ignore-map-loader:

```bash
$ npm install ignore-map-loader -D
```

## Config

Then add the loader to your webpack config. For example:

```javascript
{
    test: /\.(map)$/,
    loader: 'ignore-map-loader'
}
```
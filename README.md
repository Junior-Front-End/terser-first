# Terser-first
2022.09.30

Protect javascript source codes

## Docs

1. [terser github](https://github.com/terser/terser)
2. [terser cli](https://terser.org/docs/cli-usage)
3. [terser react](https://terser.org/docs/api-reference)

## Install

`yarn global add terser`

## Usage

```js
// Simple and unsecure:
terser index.js -c passes=2 -m --mangle-props -o output.js

// Complex: 
terser example.js -c passes=2 -m --mangle-props regex=/_$/,reserved=[bar_]

```


## terser-webpack-plugin

```js
npm i --save-dev terser-webpack-plugin

```

## Related

* [nw.js](https://docs.nwjs.io/en/latest/For%20Users/Advanced/Protect%20JavaScript%20Source%20Code/)

# cpo

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/cpo.svg?style=flat-square&logo=npm
[npm-url]: https://npmjs.org/package/cpo
[travis-image]: https://img.shields.io/travis/ant-ife/cpo.svg?style=flat-square&logo=travis
[travis-url]: https://travis-ci.org/gaius-qi/cpo
[codecov-image]: https://img.shields.io/codecov/c/github/gaius-qi/cpo.svg?style=flat-square&logo=javascript
[codecov-url]: https://codecov.io/gh/gaius-qi/cpo
[node-image]: https://img.shields.io/badge/node.js-%3E=_8-green.svg?style=flat-square&logo=node.js
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/cpo.svg?style=flat-square&logo=npm
[download-url]: https://npmjs.org/package/cpo

> Copy command output to clipboard.

## Introduction

Quick copy command output tool.

## Install

```bash
$ npm i cpo -g
```
## Usage

### Copy `pwd` output to clipboard.

```bash
$ cpo pwd
```

## Command alias

Use cpo to assist the pwd command.

### bash

Add alias in your `~/.bash_profile`

```bash
alias pwd="cpo pwd""
```

### zsh

Add alias in your `~/.zshrc`

```bash
alias pwd="cpo pwd"
```

### fish

Add alias in your `~/.config/fish/config.fish`

```bash
alias pwd "cpo pwd"
```

After adding alias, you can use the pwd command after cpo assist.



### Test project

```bash
$ npm run test
```

## Issues

- [Open an issue in GitHub](https://github.com/gaius-qi/cpo/issues)

## License

[MIT](http://opensource.org/licenses/MIT)

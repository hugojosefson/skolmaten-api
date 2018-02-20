# Unofficial API for skolmaten.se

[![Build Status](https://travis-ci.org/hugojosefson/skolmaten-api.svg?branch=master)](https://travis-ci.org/hugojosefson/skolmaten-api)
[![npm page](https://img.shields.io/npm/v/@hugojosefson/skolmaten-api.svg)](https://npmjs.com/package/@hugojosefson/skolmaten-api)
[![License ISC](https://img.shields.io/npm/l/@hugojosefson/skolmaten-api.svg)](https://tldrlegal.com/license/-isc-license)
[![SemVer 2.0.0](https://img.shields.io/badge/SemVer-2.0.0-lightgrey.svg)](http://semver.org/spec/v2.0.0.html)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

[![Waffle.io](https://img.shields.io/waffle/label/hugojosefson/skolmaten-api/inbox.svg)](https://waffle.io/hugojosefson/skolmaten-api)
[![Waffle.io](https://img.shields.io/waffle/label/hugojosefson/skolmaten-api/to%20do.svg)](https://waffle.io/hugojosefson/skolmaten-api)
[![Waffle.io](https://img.shields.io/waffle/label/hugojosefson/skolmaten-api/in%20progress.svg)](https://waffle.io/hugojosefson/skolmaten-api)
[![Waffle.io](https://img.shields.io/waffle/label/hugojosefson/skolmaten-api/done.svg)](https://waffle.io/hugojosefson/skolmaten-api)

## Introduction

This is an unofficial API module for accessing school lunch menus from [skolmaten.se](https://skolmaten.se/).

## Prerequisite

Node.js, at least `v4.0.0`.

Recommended to install latest via [nvm](https://github.com/creationix/nvm#readme):

```bash
nvm install stable
```

## Installation

```bash
npm install -g @hugojosefson/skolmaten-api
```

## Usage on CLI

```bash
skolmaten-api --help
```

Will let you know of available parameters.

## Programmatic access

You can also `import` or `require` the module, and use its exported functions programmatically.

### API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

##### Table of Contents

-   [generateGreeting](#generategreeting)
-   [identity](#identity)

#### generateGreeting

Generates a greeting

**Parameters**

-   `whom` **[String](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)** Whom to greet.

Returns **[Promise](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Promise)&lt;[String](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)>** A Promise of a greeting.

#### identity

Returns the supplied argument.

**Parameters**

-   `a` **any** Any argument.

Returns **any** The argument a.

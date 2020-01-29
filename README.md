browser-reset
===========
[![npm](https://img.shields.io/npm/v/browser-reset.svg)](https://www.npmjs.com/package/browser-reset)
> A reset stylesheet for the modern web

Browsers are inconsistent, each having their own ways of displaying things. This package aims to solve this problem by setting stylesheets back to a default look.

### Easy Installation

Just run `yarn add browser-reset` or `npm install -save browser-reset`

If you're using webpack to compile, you can use `@import '~browser-reset/reset.scss'`

If you're using postcss you can use `postcss-import` then `@import 'browser-reset/reset.css'`

If you're using a custom gulp / grunt task make sure your `includePath` for `node-sass` includes `node_modules`. Feel free to submit a issue if you have trouble setting this up.

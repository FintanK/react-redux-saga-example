# react-redux-saga-example

Inspired by https://github.com/yelouafi/redux-saga-beginner-tutorial/tree/sagas

This application provides a basic example of how redux-saga can be applied to a counter

# Background

**The whole state of your app is stored in an object tree inside a single store.
The only way to change the state tree is to emit an action, an object describing what happened.
To specify how the actions transform the state tree, you write pure reducers.**

Redux is a predictable state container for JavaScript apps.
(If you're looking for a WordPress framework, check out Redux Framework.)

It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger.

You can use Redux together with React, or with any other view library.
It is tiny (2kB, including dependencies).

**Installation**

To install the stable version:

> npm install --save redux

Other dependencies

> npm install --save react-redux
> npm install --save-dev redux-devtools

This assumes you are using npm as your package manager.

If you're not, you can access these files on unpkg, download them, or point your package manager to them.

Most commonly people consume Redux as a collection of CommonJS modules. These modules are what you get when you import redux in a Webpack, Browserify, or a Node environment. If you like to live on the edge and use Rollup, we support that as well.

If you don't use a module bundler, it's also fine. The redux npm package includes precompiled production and development UMD builds in the dist folder. They can be used directly without a bundler and are thus compatible with many popular JavaScript module loaders and environments. For example, you can drop a UMD build as a <script> tag on the page, or tell Bower to install it. The UMD builds make Redux available as a window.Redux global variable.

The Redux source code is written in ES2015 but we precompile both CommonJS and UMD builds to ES5 so they work in any modern browser. You don't need to use Babel or a module bundler to get started with Redux.

**Other dependencies / tools**



# Instructions

Setup

```
npm install
```

Run the demo

```
npm start
```

Run tests

```
npm test
```

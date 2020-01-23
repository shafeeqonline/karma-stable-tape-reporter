# karma-stable-tape-reporter [![Build Status](http://img.shields.io/travis/terinjokes/karma-stable-tape-reporter.svg?style=flat)](https://travis-ci.org/terinjokes/karma-stable-tape-reporter) [![](http://img.shields.io/npm/dm/karma-stable-tape-reporter.svg?style=flat)](https://www.npmjs.org/package/karma-stable-tape-reporter) [![](http://img.shields.io/npm/v/karma-stable-tape-reporter.svg?style=flat)](https://www.npmjs.org/package/karma-stable-tape-reporter) [![](http://img.shields.io/codeclimate/github/terinjokes/karma-stable-tape-reporter.svg?style=flat)](https://codeclimate.com/github/terinjokes/karma-stable-tape-reporter) [![](http://img.shields.io/codeclimate/coverage/github/terinjokes/karma-stable-tape-reporter.svg?style=flat)](https://codeclimate.com/github/terinjokes/karma-stable-tape-reporter)

> Karma plugin to report test results that mimics `tape`.

# Installation

`npm install --save-dev karma-stable-tape-reporter`

# Configuration

```javascript
// karma.conf.js

module.exports = function(config) {
  config.set({
    // ...

    reporters: ['tape'],

    // ...
  });
};
```

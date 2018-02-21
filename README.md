# karma-jasmine-extra-matchers

[![Code Climate](https://codeclimate.com/github/tomi77/karma-jasmine-extra-matchers/badges/gpa.svg)](https://codeclimate.com/github/tomi77/karma-jasmine-extra-matchers)
[![dependencies Status](https://david-dm.org/tomi77/karma-jasmine-extra-matchers/status.svg)](https://david-dm.org/tomi77/karma-jasmine-extra-matchers)
![Downloads](https://img.shields.io/npm/dt/karma-jasmine-extra-matchers.svg)

A [Karma](https://karma-runner.github.io/2.0/) plugin to inject [jasmine-extra-matchers](https://github.com/tomi77/jasmine-extra-matchers)

## Installation

~~~bash
npm install karma-jasmine-extra-matchers --save-dev
~~~

## Usage

Include ``jasmine-extra-matchers`` in the frameworks and ``karma-jasmine-extra-matchers`` in the plugins section of your config

~~~js
module.exports = function(config) {
  config.set({
    frameworks: [
      'jasmine',
      'jasmine-extra-matchers'
    ],
    files: [
      'src/**/*.js',
      'src/**/*.spec.js'
    ],
    // also you must add it as a plugin
    plugins: [
      'karma-jasmine',
      'karma-jasmine-extra-matchers'
    ]
  });
};
~~~

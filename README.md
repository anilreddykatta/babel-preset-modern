# babel-preset-modern

> Babel preset for modern browsers. All you need to compile your code to a ES5/ES6 hybrid.

[![NPM Version](http://img.shields.io/npm/v/babel-preset-modern.svg?style=flat-square)](https://www.npmjs.org/package/babel-preset-modern) ![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square) ![Chrome 41](https://img.shields.io/badge/Chrome-41-green.svg?style=flat-square) ![Firefox 36](https://img.shields.io/badge/Firefox-36-green.svg?style=flat-square) ![Opera 28](https://img.shields.io/badge/Opera-28-green.svg?style=flat-square) ![Safari 28](https://img.shields.io/badge/Safari-9-green.svg?style=flat-square)

* [Differences](#differences)
* [Compatibility Table](#compatibility-table)
* [Installation](#installation)
* [Usage](#usage)

## Differences

This preset is based on Babel's default [ES2015 preset](https://babeljs.io/docs/plugins/preset-es2015/).

#### Removed Plugins

- [transform-es2015-block-scoping](https://babeljs.io/docs/plugins/transform-es2015-block-scoping)
- [transform-es2015-for-of](https://babeljs.io/docs/plugins/transform-es2015-for-of)
- [transform-es2015-function-name](https://babeljs.io/docs/plugins/transform-es2015-function-name)
- [transform-es2015-literals](https://babeljs.io/docs/plugins/transform-es2015-literals)
- [transform-es2015-template-literals](https://babeljs.io/docs/plugins/transform-es2015-template-literals)
- [transform-es2015-typeof-symbol](https://babeljs.io/docs/plugins/transform-es2015-typeof-symbol)

## Compatibility Table

ES6 modules are always in strict mode.

<table width="100%">
    <thead>
        <th>Feature</th>
        <th>Chrome</th>
        <th>Firefox (Gecko)</th>
        <th>Opera</th>
        <th>Safari</th>
    </thead>
    <tr>
        <td>
            <code>const</code>
        </td>
        <td>41</td>
        <td>36 (36)</td>
        <td>28</td>
        <td>5.1</td>
    </tr>
    <tr>
        <td>
            <code>let</code>
        </td>
        <td>41</td>
        <td>35 (35)</td>
        <td>28</td>
        <td>(Yes)</td>
    </tr>
    <tr>
        <td colspan="5">
            &#8627; <a href="https://babeljs.io/docs/plugins/transform-es2015-block-scoping">transform-es2015-block-scoping</a> (also known as “lexical declarations”)
        </td>
    </tr>
    <tr>
        <td>
            <code>for...of</code>
        </td>
        <td>38</td>
        <td>13 (13)</td>
        <td>25</td>
        <td>7.1</td>
    </tr>
    <tr>
        <td colspan="5">
            &#8627; <a href="https://babeljs.io/docs/plugins/transform-es2015-for-of">transform-es2015-for-of</a>
        </td>
    </tr>
    <tr>
        <td>
            <code>Function.name</code>
        </td>
        <td>33</td>
        <td>(Yes)</td>
        <td>(Yes)</td>
        <td>(Yes)</td>
    </tr>
    <tr>
        <td colspan="5">
            &#8627; <a href="https://babeljs.io/docs/plugins/transform-es2015-function-name">transform-es2015-function-name</a>
        </td>
    </tr>
    <tr>
        <td>
            <code>Template strings</code>
        </td>
        <td>41</td>
        <td>34</td>
        <td>28</td>
        <td>9</td>
    </tr>
    <tr>
        <td colspan="5">
            &#8627; <a href="https://babeljs.io/docs/plugins/transform-es2015-template-literals">transform-es2015-template-literals</a>
        </td>
    </tr>
    <tr>
        <td>
            <code>typeof Symbol</code>
        </td>
        <td>38</td>
        <td>36 (36)</td>
        <td>25</td>
        <td>9</td>
    </tr>
    <tr>
        <td colspan="5">
            &#8627; <a href="https://babeljs.io/docs/plugins/transform-es2015-typeof-symbol">transform-es2015-typeof-symbol</a>
        </td>
    </tr>
</table>

## Installation

```sh
$ npm install --save-dev babel-preset-modern
```

## Usage

Add the following line to your `.babelrc` file:

```json
{
  "presets": ["modern"]
}

```
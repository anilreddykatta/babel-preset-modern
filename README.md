# babel-preset-modern

> Babel preset for modern browsers.

[![NPM Version](http://img.shields.io/npm/v/babel-preset-modern.svg?style=flat-square)](https://www.npmjs.org/package/babel-preset-modern) ![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square) ![Chrome 41](https://img.shields.io/badge/Chrome-41-green.svg?style=flat-square) ![Firefox 36](https://img.shields.io/badge/Firefox-36-green.svg?style=flat-square) ![Opera 28](https://img.shields.io/badge/Opera-28-green.svg?style=flat-square) ![Safari 28](https://img.shields.io/badge/Safari-9-green.svg?style=flat-square)

## Compatibility Table

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
            <code>for...of</code>
        </td>
        <td>38</td>
        <td>13 (13)</td>
        <td>25</td>
        <td>7.1</td>
    </tr>
    <tr>
        <td>
            <code>const</code>
        </td>
        <td>21</td>
        <td>36 (36)</td>
        <td>12</td>
        <td>5.1</td>
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
        <td>
            <code>typeof Symbol</code>
        </td>
        <td>38</td>
        <td>36 (36)</td>
        <td>25</td>
        <td>9</td>
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
</table>

## Install

```sh
$ npm install --save-dev babel-preset-modern
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["modern"]
}
```

### Via CLI

```sh
$ babel script.js --presets modern 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["modern"]
});
```

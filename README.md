# csp-preset-google-analytics
Google Analytics preset for [csp-header](https://github.com/frux/csp/tree/master/packages/csp-header#readme)

![npm](https://img.shields.io/npm/v/csp-preset-google-analytics)
![npm](https://img.shields.io/npm/dw/csp-preset-google-analytics)

## Installation
```
npm install --save csp-preset-google-analytics
```

## Usage
```js
const { getCSP } = require('csp-header');

const my_csp_policy = getCSP({
    directives: {
        // Your directives
    },
    presets: [
        // Add the Google Analytics
        require("csp-preset-google-analytics"),
    ]
});
```

## Contribute
Feel free to open issues/pull-requests if a directive is missing.
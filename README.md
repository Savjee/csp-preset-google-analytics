# csp-preset-google-analytics
Google Analytics preset for [csp-header](https://github.com/frux/csp/tree/master/packages/csp-header#readme)

Installation:
```
npm install --save csp-preset-google-analytics
```

Usage:
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

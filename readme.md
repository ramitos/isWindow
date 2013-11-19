# isWindow

based on [jquery/jquery](https://github.com/jquery/jquery/blob/a5037cb9e3851b171b49f6d717fb40e59aa344c2/src/core.js#L226-L228)

## install

```bash
component install isWindow
```

## api

```js
var isWindow = require('isWindow')

isWindow(document.body) // => false
isWindow(window) // => true
```
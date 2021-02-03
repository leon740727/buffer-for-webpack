# buffer-for-webpack
a node buffer polyfill for webpack 5

## useage

1. install

`npm install git://github.com/leon740727/buffer-for-webpack.git`

2. update your webpack.config.js to something like this...

```js
const webpack = require('webpack');

module.exports = {
  ...
  plugins: [
    new webpack.ProvidePlugin({
      Buffer: 'buffer-for-webpack',
    }),
  ],
  ...
}
```

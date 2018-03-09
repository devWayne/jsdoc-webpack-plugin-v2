jsdoc-webpack-plugin-v4
==========================


WebPack plugin that runs [jsdoc](http://usejsdoc.org/) on your bundles

# Install
```
npm i jsdoc-webpack-plugin-v4 --save
````

# Usage
In webpack.config.js:
```javascript
var webpack = require('webpack');
var JsDocPlugin = require('jsdoc-webpack-plugin-v4');

module.exports = {
    /// ... rest of config
    plugins: [
        new JsDocPlugin({
            conf: path.join(__dirname, 'jsdoc.json'),
        })
    ]
}

```

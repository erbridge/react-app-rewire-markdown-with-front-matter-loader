# react-app-rewire-markdown-with-front-matter-loader

Add [`markdown-with-front-matter-loader`](https://github.com/matthewwithanm/markdown-with-front-matter-loader) to a [`react-app-rewired`](https://github.com/timarney/react-app-rewired) config.

```js
/* config-overrides.js */

const rewireMarkdown = require('react-app-rewire-markdown-with-front-matter-loader');

module.exports = (config, env) => {
  // ...
  config = rewireMarkdown(config, env);
  // ...
  return config;
};
```

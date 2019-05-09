```
$ yarn build
yarn run v1.7.0
$ webpack
Hash: ce8c5a09d7e5eefc63e5
Version: webpack 4.30.0
Time: 236ms
Built at: 05/09/2019 11:41:37 AM
  Asset      Size  Chunks             Chunk Names
main.js  24.5 KiB       0  [emitted]  main
Entrypoint main = main.js
[0] ./src/index.js 39 bytes {0} [built]
[2] ./node_modules/contentful-ui-extensions-sdk/dist sync 160 bytes {0} [built]
    + 1 hidden module

WARNING in ./node_modules/contentful-ui-extensions-sdk/dist/cf-extension-api.js 1:292-296
Critical dependency: the request of a dependency is an expression
 @ ./src/index.js

WARNING in configuration
The 'mode' option has not been set, webpack will fallback to 'production' for this value. Set 'mode' option to 'development' or 'production' to enable defaults for each environment.
You can also set it to 'none' to disable any default behavior. Learn more: https://webpack.js.org/concepts/mode/
✨  Done in 1.28s.
```

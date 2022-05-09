# wp5-cra-polyfill
 
An automatic polyfill hook for the latest `create-react-app` which injects `node-polyfill-webpack-plugin` to the config

* it modifies the `react-scripts/config/webpack.config.js` in the `module` and the `cache` location
* it includes a fallback for `create-react-app` to operate usual if this package were to be uninstalled

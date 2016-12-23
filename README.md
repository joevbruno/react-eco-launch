# react-eco-launch
A starter kit / boilerplate for react-ecosystem stuff

# Setup
-[] Latest LST node
- [] yarn
- [] Huskey

# Compiling
- [] app-root-dir
- [] code-split-component
- [] compression (in Webpack client)
- [] dotenv
- [] source-map-support
file-size
"chokidar": "1.6.1",
"glob": "7.1.1",
"node-notifier": "4.6.1",
"rimraf": "2.5.4",
"semver": "5.3.0",
cross-env
https://github.com/FormidableLabs/nodejs-dashboard?utm_source=SitePoint&utm_medium=email&utm_campaign=Versioning

## Webpack
- [] Webpack:
- [] Webpack Assets Plugin
"happypack": "3.0.1",
"html-webpack-plugin": "2.24.1",
"css-loader": "0.26.1",
"file-loader": "0.9.0",
"json-loader": "0.5.4",
"md5": "2.2.1",
"style-loader": "0.13.1",
"webpack": "2.1.0-beta.28",
"webpack-bundle-analyzer": "2.1.1",
"webpack-dev-middleware": "1.8.4",
"webpack-hot-middleware": "2.13.2",
"webpack-md5-hash": "0.0.5",
"webpack-node-externals": "1.5.4"
friendly-errors-webpack-plugin
webpack dashboard
webpack-isomorphic-tools
 "webpack-bundle-analyzer": "2.1.1",
    "webpack-dev-middleware": "1.9.0",
    "webpack-hot-middleware": "2.13.2",
    "webpack-md5-hash": "0.0.5"
webpack validator

### Webpack Plugins
https://github.com/soundcloud/chunk-manifest-webpack-plugin

## Polyfills
polyfill.io
"regenerator-runtime": "0.10.1",

## Babel
  "babel-plugin-transform-object-rest-spread": "6.20.2",
  "babel-plugin-transform-react-jsx-self": "6.11.0",
  "babel-plugin-transform-react-jsx-source": "6.9.0",
  "babel-plugin-react-transform": "2.0.0",
  "babel-plugin-transform-decorators-legacy": "1.3.4",
       "syntax-trailing-function-commas",
  "babel-plugin-transform-react-constant-elements": "6.9.1",
  "babel-plugin-transform-react-inline-elements": "6.8.0",
  https://www.npmjs.com/package/babel-plugin-typecheck
  babel-preset-react-optimize
      "babel-plugin-react-intl": "^2.1.1",

  "babel-preset-env": "1.0.2",
  "babel-preset-latest": "6.16.0",
  "babel-preset-react": "6.16.0"
  "babel-plugin-module-resolver": "2.4.0",
  "babel-plugin-transform-async-to-generator": "6.16.0",
  "babel-plugin-transform-class-properties": "6.19.0",
  transform-runtime?
 
## Dev
"react-hot-loader": "3.0.0-beta.6",
browser-sync


# Testing
- [] Jest
- [] Expect
- [] enzyme
- [] jsdom
    "babel-jest": "17.0.2",

invariant
react-addons-test-utils

# Types
"flow-bin": "0.37.0",
"flow-coverage-report": "0.2.0",
"flow-remove-types": "1.1.2",
"flow-typed": "2.0.0",

# Quality
- Eslint / Babel Eslint
"eslint": "3.12.1",
"eslint-config-airbnb": "13.0.0",
"eslint-plugin-flowtype": "2.29.1",
"eslint-plugin-import": "2.2.0",
"eslint-plugin-jsx-a11y": "2.2.3",
"eslint-plugin-react": "6.8.0",
    "eslint-plugin-css-modules": "^1.0.9",
    "stylelint": "^7.6.0",
    "stylelint-config-standard": "^15.0.0",

codeclimate-test-reporter

# CI Services
- [] 
raven-js

# Deploying
- [] Docker
- [] AWS(?)

# API Server
- [] express
 "body-parser": "^1.15.2",
 serve-favicon
 morgan 
"cookie-parser": "^1.3.5",
"debug": "^2.0.0",
multer
nodemailer
passport

    "socket.io": "^1.3.7",
    "socket.io-client": "^1.3.7",

# DB
connect-mongo
    
# API Security
bcrypt
- [] uuid
- [] helmet
- [] hpp
- [] serialize-javascript
- [] sanitizer
https://www.npmjs.com/package/letsencrypt-express
https://github.com/electrode-io/electrode-csrf-jwt

# Offline / Perf
- [] Offline Plugin
- [] fastclick
https://www.npmjs.com/package/localforage


# Styles
- [] Normalize.css
- [] Modernizer
"extract-text-webpack-plugin": "2.0.0-beta.4",
postcss / autoprefixing / fix flex bugs
styled-components
"classnames": "^2.2.5",
color: https://www.npmjs.com/package/color 
chroma-js
font-face observer

# Internationalization
https://github.com/ctrlplusb/react-universally/issues/254
"intl": "^1.0.0",
    "intl-locales-supported": "^1.0.0",
    "intl-messageformat": "^1.1.0",
    "intl-relativeformat": "^1.1.0",

# SSR
https://github.com/electrode-io/electrode-react-ssr-caching


# React
- [] Use Preact(?)
- [] React-dom
- [] react-addons-pure-render-mixin
- [] react-router 4
- [] Use react-virtualized?
- [] react-helmet
 "react-gravatar": "^2.4.4",
    "react-intl": "^2.1.2",
- [] CSS transition group
react-deep-force-update

# Redux
- [] redux-thunk, sagas, observable, logic, modules
- [] redux-search
- [] redux analytics middleware
multireducer
https://www.npmjs.com/package/redux-async-connect
redux-form
https://www.npmjs.com/package/violet-paginator
 "redux-logger": "^2.7.4",
    "redux-observable": "^0.12.1",
    "redux-persist": "4.0.0-beta1",
   "redux-devtools": "^3.0.0-beta-3",
    "redux-devtools-dock-monitor": "^1.0.0-beta-3",
    "redux-devtools-log-monitor": "^1.0.0-beta-3",
    redux-immutable-state-invariant

# MapStateToProps
- [] selectors paradigm
- [] reselect

# Other Libs
- [] RxJs
immutablejs
- [] D3 / Victory (?)
- [] Ramda
- [] moment
  "gravatar-api": "^1.4.0",
  https://www.npmjs.com/package/obey

# Utilitity Type
https://www.npmjs.com/package/slug
shallowequal
https://www.npmjs.com/package/query-string
- [] mimetypes
numeral
https://github.com/RickWong/fetch-plus


## Keep in mind
https://github.com/madrobby/keymaster
https://github.com/noeldelgado/react-gemini-scrollbar

## Image Processing
https://www.npmjs.com/package/sharp
react-dropzone

  


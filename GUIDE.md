# How to set up React, Webpack, and Babel: what you will learn 

Made the tutorial https://www.valentinog.com/blog/babel/

## Inizialize the project
```
mkdir my-app && cd $_
mkdir -p src
npm init -y
```

## Install packages
* Static module bundler
```
npm i webpack webpack-cli --save-dev
```
* JavaScript compiler
```
npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
```
* Lib
```
npm i react react-dom
```
* Document the components
```
npm i prop-types --save-dev
```
* Processing HTML to Webpack
```
npm i html-webpack-plugin html-loader --save-dev
```
* Set dev server
```
npm i webpack-dev-server --save-dev
```

## Set scripts in package.json

```
"start": "webpack-dev-server --open --mode development"

"build": "webpack --mode production"
```

## Add webpack.config.js
## Add .babelrc
## Have fun programming

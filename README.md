# Webpack 5

## Install

```
npm init -y
npm i -D webpack webpack-cli
```

## Plugins

```
npm i -D html-webpack-plugin
// npm i -D clean-webpack-plugin
```

### html-webpack-plugin

- mount js to html automatically

### clean-webpack-plugin (don't need in webpack 5)

- clean the build folder

```
output: {
    clean: true,
}
```

## Module (Loaders)

### Babel

```
npm i -D babel-loader @babel/core @babel/preset-env @babel/preset-env @babel/plugin-proposal-class-properties
touch .babelrc
```

- add to `.babelrc`

```
{
  "presets": ["@babel/preset-env"],
  "plugins": ["@babel/plugin-proposal-class-properties"]
}
```

### Assets

#### Images

#### Fonts & SVG

### Styles (css)

```
npm i -D sass-loader postcss-loader css-loader style-loader postcss-preset-env node-sass
```

## webpack-dev-server

```
npm i -D webpack-dev-server
```

## Refs

- https://segmentfault.com/a/1190000037554402



## Setup

```bash
brew update
brew install yarn
```

## Run this app

```
yarn install
yarn start
```

## Steps taken to produce this project

This application was built using the [scotch.io tutorial](https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel), but I wanted to extract a few things that were done to get this project up and running:

```bash
yarn init
yarn add webpack webpack-dev-server path
touch webpack.config.js # insert webpack config w/ text editor
yarn add babel-loader babel-core babel-preset-es2015 babel-preset-react --dev
touch .babelrc # insert babel config w/ text editor

# create client directory and html template

yarn add html-webpack-plugin
```

## References

- https://yarnpkg.com/en/docs/install
- https://webpack.github.io/docs/
- https://webpack.js.org/
- https://babeljs.io/
- https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel

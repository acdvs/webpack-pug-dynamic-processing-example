## About

An example barebones project for dynamically processing all Pug templates in a directory to output individual HTML files.

Based on a Stack Overflow question: [Can Webpack build multiple HTML files from SCSS and Pug?](https://stackoverflow.com/q/52176542/4881192)

## Function

Uses [`html-webpack-pug-plugin`](https://github.com/negibouze/html-webpack-pug-plugin) and [`html-webpack-plugin`](https://webpack.js.org/plugins/html-webpack-plugin) to loop through a given directory that contains Pug files and outputs the resulting HTML file for each template in another directory via a simple loop in the Webpack configuration.
# Stylescape Webpack Example

This example demonstrates how to integrate [Stylescape](https://github.com/stylescape/stylescape) with [Webpack](https://webpack.js.org/), a powerful module bundler for JavaScript applications.

## About Stylescape

Stylescape is a comprehensive design system and CSS framework that provides a complete toolkit for building modern, accessible, and responsive web interfaces. It includes layout systems, interactive components, and utility classes.

## Installation

```sh
git clone https://github.com/stylescape/example-webpack.git
cd example-webpack
npm install
```

## Usage

### Development Server

```sh
npm start
```

This starts the Webpack development server with hot module replacement.

### Production Build

```sh
npm run build
```

Builds optimized and minified assets for production.

## Project Structure

```
example-webpack/
├── src/
│   ├── index.html      # Main HTML entry point
│   ├── js/             # JavaScript source files
│   └── scss/           # Sass stylesheets
├── package.json        # Dependencies and scripts
└── webpack.config.js   # Webpack configuration
```

## Features Demonstrated

- Importing Stylescape via npm
- Sass compilation with sass-loader
- JavaScript bundling and optimization
- Development server with live reload

## Learn More

- [Stylescape Documentation](https://github.com/stylescape/stylescape)
- [Webpack Documentation](https://webpack.js.org/)

## License

MIT

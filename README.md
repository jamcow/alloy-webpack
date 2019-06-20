# Alloy (Webpack)

**A Jekyll Boilerplate With Laravel Mix**

Borrowed [Jekyll Mix](https://github.com/fredericpfisterer/jekyll-mix) as a starter...

Future work aiming to have standalone Jekyll and concurrent Sass compilation for sites. And as fast and optimised as possible.

## Current issues

* Jekyll doesn't trigger refresh on HTML change, Sass/JS does

## Features

* ES2017 + modules compilation (Webpack + Babel)
* BrowserSync
* Sass
* PostCSS Autoprefixer
* Sourcemaps in Dev
* Minification in Production
* Versionning in Production
* Include Media (http://include-media.com)

## Requirements

* node
* Jekyll
* npm or Yarn
* shipit (https://github.com/shipitjs/shipit)

## Installation

```yarn```

### Development

```yarn watch```

### Static build

```yarn production```

## Deployment

Edit shipitfile.js

then :

```shipit staging deploy```

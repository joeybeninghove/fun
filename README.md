# Fun

A simple little toolkit for quick prototyping and experimenting with web
UIs.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

A node package manager, I recommend installing [Yarn](https://yarnpkg.com/en/)
via [Homebrew](https://brew.sh/).

```bash
brew install yarn
```

### Installing

This will install all the necessary node packages for this project.

```bash
yarn install
```

## Usage

Everything is already preconfigured to use [Webpack](https://webpack.js.org/)
to package everything up into the `/public` directory and start a browser sync
session at [http://localhost:9000](http://localhost:9000).

Just run these commands to build everything and automatically open your
default browser to the page.  :tada:

```bash
webpack --watch
```

## Structure

* **src** - _everything in here gets built by Webpack_
  * **controllers/** - _Stimulus controllers go here_
  * **styles/** - _CSS styles go here_
  * **index.js** - _main entry point for Webpack_
  * **index.html** - _main HTML file_
* **package.json** - _node packages_
* **postcss.config.js** - _PostCSS config, mainly to load Tailwind_
* **tailwind.js** - _Tailwind CSS config_
* **webpack.config.js** - _main Webpack config_

## Built With

### [Webpack](https://webpack.js.org/)
Everything is configured using Webpack to package up the HTML and assets.  The
`/webpack.config.js` file is the place to go to see how it's all set up.

### [Babel](https://babeljs.io/)
Babel and related plugins to allow writing javascript of the future (e.g. ES6)
and have it transpiled for today's browsers.

### [Tailwind CSS](https://tailwindcss.com)
The best little CSS utility framework out there.  Tailwind is the best way I've
found to rapidly build web UIs.  The Tailwind config can be customized in
`/tailwind.js`.

### [Stimulus](https://stimulusjs.org/)
Super lightweight javascript framework for dealing with simple interactions
among DOM elements.

### [Browsersync](https://browsersync.io/)
Must-have tool for not having to ever hit the refresh button again during
development.

## Contributing

Coming soon...

## Versioning

No versioning yet, since it's just a repo right now.  If this gets turned into
its own NPM package, then the versioning will begin.  :smile:

## Authors

* Joey Beninghove - [joey.io](https://joey.io)

## License

This project is licensed under the MIT License - see the
[LICENSE.md](LICENSE.md) file for details.

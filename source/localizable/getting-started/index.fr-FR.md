Débuter avec Ember est facile. Les projets Ember sont créés et gérés par notre outil en ligne de commande Ember CLI. Cet outil fournit :

* Modern application asset management (including concatenation, minification, and versioning).
* Generators to help create components, routes, and more.
* A conventional project layout, making existing Ember applications easy to approach.
* Support for ES2015/ES6 JavaScript via the [Babel](http://babeljs.io/docs/learn-es2015/) project. This includes support for [JavaScript modules](http://exploringjs.com/es6/ch_modules.html), which are used throughout this guide.
* A complete [QUnit](https://qunitjs.com/) test harness.
* The ability to consume a growing ecosystem of [Ember Addons](https://emberobserver.com/).

## Dependencies

### Git

Ember requires Git to manage many of its dependencies. Git comes with Mac OS X and most Linux distributions. Windows users can download and run [this Git installer](http://git-scm.com/download/win).

### Nodes.js et npm

Ember CLI is built with JavaScript, and expects the [Node.js](https://nodejs.org/) runtime. It also requires dependencies fetched via [npm](https://www.npmjs.com/). npm is packaged with Node.js, so if your computer has Node.js installed you are ready to go.

Ember requires Node.js 0.12 or higher and npm 2.7 or higher. If you're not sure whether you have Node.js or the right version, run this on your command line:

```bash
node --version
npm --version
```

If you get a *"command not found"* error or an outdated version for Node:

* Windows or Mac users can download and run [this Node.js installer](http://nodejs.org/en/download/).
* Mac users often prefer to install Node using [Homebrew](http://brew.sh/). After installing Homebrew, run `brew install node` to install Node.js.
* Linux users can use [this guide for Node.js installation on Linux](https://nodejs.org/en/download/package-manager/).

If you get an outdated version of npm, run `npm install -g npm`.

### Bower

Ember requires Bower to manage additional dependencies. Bower is a command line utility that you install with npm. To install Bower run, ```npm install -g bower```

### Watchman (optionnel)

On Mac and Linux, you can improve file watching performance by installing [Watchman](https://facebook.github.io/watchman/docs/install.html).

### PhantomJS (optional)

You can run your tests from the command line with PhantomJS, without the need for a browser to be open. Consult the [PhantomJS download instructions](http://phantomjs.org/download.html).

## Installation

Installez Ember en utilisant npm :

```bash
npm install -g ember-cli
```

Pour vérifier que l'installation fonctionne, exécuter :

```bash
ember -v
```

Si un numéro de version s'affiche, Ember est bien installé.
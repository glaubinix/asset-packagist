# Asset Packagist

[![Latest Stable Version](https://poser.pugx.org/hiqdev/asset-packagist/v/stable)](https://packagist.org/packages/hiqdev/asset-packagist)
[![Total Downloads](https://poser.pugx.org/hiqdev/asset-packagist/downloads)](https://packagist.org/packages/hiqdev/asset-packagist)
[![Build Status](https://img.shields.io/travis/hiqdev/asset-packagist.svg)](https://travis-ci.org/hiqdev/asset-packagist)
[![Scrutinizer Code Coverage](https://img.shields.io/scrutinizer/coverage/g/hiqdev/asset-packagist.svg)](https://scrutinizer-ci.com/g/hiqdev/asset-packagist/)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/hiqdev/asset-packagist.svg)](https://scrutinizer-ci.com/g/hiqdev/asset-packagist/)

![Composer](https://raw.githubusercontent.com/hiqdev/asset-packagist/master/docs/asset-packagist.png)

## Composer + Bower + NPM = friends forever!

This package is the core part of https://asset-packagist.org/ project.

Asset Packagist allows installation of Bower and NPM packages as native
Composer packages.

**NO** plugins and **NO** Node.js are required.

## Installation

You don't need to install anything to use Asset Packagist!

If you want to setup your own version of Asset Packagist
please see installation instruction at [hiqdev/asset-packagist.dev]

[hiqdev/asset-packagist.dev]: https://github.com/hiqdev/asset-packagist.dev

## Usage

List required packages like the following:

```php
"require": {
    "bower-asset/bootstrap": "^3.3",
    "npm-asset/jquery": "^2.2"
}
```

And add these lines:</p>

```php
"repositories": [
    {
        "type": "composer",
        "url": "https://asset-packagist.org"
    }
]
```

More information can be found on [about page](https://asset-packagist.org/site/about).

## License

This project is released under the terms of the BSD-3-Clause [license](LICENSE).
Read more [here](http://choosealicense.com/licenses/bsd-3-clause).

Copyright © 2016-2018, HiQDev (http://hiqdev.com/)

## Acknowledgments

This project uses Francois Pluchino's [composer-asset-plugin] to convert Bower and NPM packages to composer format.

[composer-asset-plugin]: https://github.com/fxpio/composer-asset-plugin

Package Skeleton
================

[![Build Status](http://img.shields.io/travis/SammyK/package-skeleton.svg)](https://travis-ci.org/SammyK/package-skeleton)
[![Total Downloads](http://img.shields.io/packagist/dm/sammyk/package-skeleton.svg)](https://packagist.org/packages/sammyk/package-skeleton)
[![Latest Stable Version](http://img.shields.io/packagist/v/sammyk/package-skeleton.svg)](https://packagist.org/packages/sammyk/package-skeleton)
[![License](http://img.shields.io/badge/license-MIT-lightgrey.svg)](https://packagist.org/packages/sammyk/package-skeleton)


:package_description

- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)


Installation
------------

Add the package-skeleton package to your `composer.json` file.

``` json
{
    "require": {
        "sammyk/package-skeleton": "~1.0"
    }
}
```

Or via the command line in the root of your Laravel installation.

``` bash
$ composer require sammyk/package-skeleton ~1.0
```

Usage
-----

``` php
$skeleton = new SammyK\Skeleton();
echo $skeleton->echoPhrase('Hello, World!');

```


Testing
-------

``` bash
$ phpunit
```


Contributing
------------

Please see [CONTRIBUTING](https://github.com/SammyK/package-skeleton/blob/master/CONTRIBUTING.md) for details.


Credits
-------

- [Sammy Kaye Powers](https://github.com/SammyK)
- [All Contributors](https://github.com/SammyK/package-skeleton/contributors)


License
-------

The MIT License (MIT). Please see [License File](https://github.com/SammyK/package-skeleton/blob/master/LICENSE) for more information.

Package Skeleton
================

[![Build Status](https://travis-ci.org/SammyK/PKGName.png?branch=master)](https://travis-ci.org/SammyK/PKGName)
[![Total Downloads](https://poser.pugx.org/sammyk/pkg-name/downloads.png)](https://packagist.org/packages/sammyk/pkg-name)
[![Latest Stable Version](https://poser.pugx.org/sammyk/pkg-name/v/stable.png)](https://packagist.org/packages/sammyk/pkg-name)
[![License](https://poser.pugx.org/sammyk/pkg-name/license.png)](https://packagist.org/packages/sammyk/pkg-name)


:package_description

- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)


Installation
------------

Add the :package_name package to your `composer.json` file:

``` json
{
    "require": {
        "sammyk/:package_name": "~1.0"
    }
}
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

Please see [CONTRIBUTING](https://github.com/SammyK/:package_name/blob/master/CONTRIBUTING.md) for details.


Credits
-------

- [Sammy Kaye Powers](https://github.com/SammyK)
- [All Contributors](https://github.com/SammyK/:package_name/contributors)


License
-------

The MIT License (MIT). Please see [License File](https://github.com/SammyK/:package_name/blob/master/LICENSE) for more information.

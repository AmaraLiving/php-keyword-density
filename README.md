# PHP Keyword Density, Word Frequency

[![Latest Version on Packagist](https://img.shields.io/packagist/v/amara/keyword-density.svg?style=flat-square)](https://packagist.org/packages/amara/keyword-density)
[![Build](https://github.com/AmaraLiving/php-keyword-density/actions/workflows/ci-build.yml/badge.svg)](https://github.com/AmaraLiving/php-keyword-density/actions/workflows/ci-build.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/amara/keyword-density.svg?style=flat-square)](https://packagist.org/packages/amara/keyword-density)

Calculates the keyword density of a text as described in [Wikipedia](https://en.wikipedia.org/wiki/Keyword_density). Counts the frequency usage of each word in a text.

Keyword density is the percentage of times a keyword or phrase appears on a text compared to the total number of words on the text. The word frequency counter PHP package can be used to count the frequency usage of each word in a text.

## Installation

> **Requires [PHP 8.0+](https://php.net/releases/)**

You can install the package via composer:

```bash
composer require masroore/keyword-density
```

## Usage

```php
$kw = new Kaiju\KeywordDensity\KeywordDensity();
$kw->setText($text);
print_r($kw->getPopularWords());
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Thank you for considering to contribute to this project. All the contribution guidelines are
mentioned [here](CONTRIBUTING.md).

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Masroor Ehsan](https://github.com/masroore)
- [All Contributors](../../contributors)

## License

This project is an open-sourced software licensed under the [MIT license](LICENSE.md).

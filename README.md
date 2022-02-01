<!-- # A tool to make email templates in Statamic v3

[![Latest Version on Packagist](https://img.shields.io/packagist/v/digiti/statamic-crow.svg?style=flat-square)](https://packagist.org/packages/digiti/statamic-crow)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/digiti/statamic-crow/run-tests?label=tests)](https://github.com/digiti/statamic-crow/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/digiti/statamic-crow/Check%20&%20fix%20styling?label=code%20style)](https://github.com/digiti/statamic-crow/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/digiti/statamic-crow.svg?style=flat-square)](https://packagist.org/packages/digiti/statamic-crow)

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example. -->

## Installation

You can install the package via composer:

```bash
composer require digiti/statamic-crow
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="statamic-crow-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="statamic-crow-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="statamic-crow-views"
```

## Usage

```php
$statamicCrow = new digiti\StatamicCrow();
echo $statamicCrow->echoPhrase('Hello, digiti!');
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Jan Janssens](https://github.com/digiti)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

# Bittrex PHP Client

[![Build Status](https://img.shields.io/travis/faustbrian/Bittrex-PHP-Client/master.svg?style=flat-square)](https://travis-ci.org/faustbrian/Bittrex-PHP-Client)
[![PHP from Packagist](https://img.shields.io/packagist/php-v/faustbrian/bittrex-php-client.svg?style=flat-square)]()
[![Latest Version](https://img.shields.io/github/release/faustbrian/Bittrex-PHP-Client.svg?style=flat-square)](https://github.com/faustbrian/Bittrex-PHP-Client/releases)
[![License](https://img.shields.io/packagist/l/faustbrian/Bittrex-PHP-Client.svg?style=flat-square)](https://packagist.org/packages/faustbrian/Bittrex-PHP-Client)

## Installation

Require this package, with [Composer](https://getcomposer.org/), in the root directory of your project.

``` bash
$ composer require faustbrian/bittrex-php-client
```

## Usage

```php
use BrianFaust\Bittrex\Bittrex;

$client = new Bittrex('key', 'secret');

dump($client->getWithdrawalHistory('BTC'));
```

## Testing

``` bash
$ phpunit
```

## Security

If you discover a security vulnerability within this package, please send an e-mail to hello@brianfaust.me. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://brianfaust.me)

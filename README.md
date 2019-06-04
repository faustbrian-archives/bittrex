# Bittrex PHP Client

[![Build Status](https://img.shields.io/travis/plients/Bittrex-PHP-Client/master.svg?style=flat-square)](https://travis-ci.org/plients/Bittrex-PHP-Client)
[![PHP from Packagist](https://img.shields.io/packagist/php-v/plients/bittrex.svg?style=flat-square)]()
[![Latest Version](https://img.shields.io/github/release/plients/Bittrex-PHP-Client.svg?style=flat-square)](https://github.com/plients/Bittrex-PHP-Client/releases)
[![License](https://img.shields.io/packagist/l/plients/Bittrex-PHP-Client.svg?style=flat-square)](https://packagist.org/packages/plients/Bittrex-PHP-Client)

## Installation

Require this package, with [Composer](https://getcomposer.org/), in the root directory of your project.

``` bash
$ composer require plients/bittrex
```

## Usage

```php
use Plients\Bittrex\Bittrex;

$client = new Bittrex('key', 'secret');

dump($client->getWithdrawalHistory('BTC'));
```

## Testing

``` bash
$ phpunit
```

## Security

If you discover a security vulnerability within this package, please send an e-mail to hello@basecode.sh. All security vulnerabilities will be promptly addressed.

## Credits

- [Brian Faust](https://github.com/faustbrian)
- [All Contributors](../../contributors)

## License

[MIT](LICENSE) © [Brian Faust](https://basecode.sh)

# Wrapper around PHP Stan rules repositories

[![Total Downloads](https://poser.pugx.org/wyrihaximus/phpstan-rules-wrapper/downloads.png)](https://packagist.org/packages/wyrihaximus/phpstan-rules-wrapper/stats)
[![License](https://poser.pugx.org/wyrihaximus/phpstan-rules-wrapper/license.png)](https://packagist.org/packages/wyrihaximus/phpstan-rules-wrapper)

# Installation

To install via [Composer](http://getcomposer.org/), use the command below, it will automatically detect the latest version and bind it with `^`.

```bash
composer require wyrihaximus/phpstan-rules-wrapper 
```

# Usage 

```neon
includes:
	- vendor/wyrihaximus/phpstan-rules-wrapper/wrapper.neon
```

# Included rulesets

* [`localheinz/phpstan-rules`](https://packagist.org/packages/localheinz/phpstan-rules)
* [`pepakriz/phpstan-exception-rules`](https://packagist.org/packages/pepakriz/phpstan-exception-rules)
* [`phpstan/phpstan-deprecation-rules`](https://packagist.org/packages/phpstan/phpstan-deprecation-rules)
* [`phpstan/phpstan-php-parser`](https://packagist.org/packages/phpstan/phpstan-php-parser)
* [`phpstan/phpstan-phpunit`](https://packagist.org/packages/phpstan/phpstan-phpunit)
* [`phpstan/phpstan-strict-rules`](https://packagist.org/packages/phpstan/phpstan-strict-rules)
* [`thecodingmachine/phpstan-safe-rule`](https://packagist.org/packages/thecodingmachine/phpstan-safe-rule)
* [`thecodingmachine/phpstan-strict-rules`](https://packagist.org/packages/thecodingmachine/phpstan-strict-rules)

# License

Copyright (c) 2019 Cees-Jan Kiewiet

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

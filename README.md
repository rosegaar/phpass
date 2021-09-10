# Portable PHP password hashing framework. (PHPass)

![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/rosegaar/phpass.svg?label=version) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Written by Solar Designer <solar at openwall.com> in 2004-2006 and placed in
the public domain.  Revised in subsequent years, still public domain.

There's absolutely no warranty.

The homepage URL for this framework is: http://www.openwall.com/phpass/

## Installation

```shell
composer require rosegaar/phpass
```

# Usage

```php
use Rosegaar\PHPass\PHPass;

$hasher = new PHPass(8, true);
$password = $hasher->HashPassword('password');
```

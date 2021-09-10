# Portable PHP password hashing framework. (PHPass)

Version 0.5 / genuine.

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
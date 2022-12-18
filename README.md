# PHP Size Byte

This library converts given size into human-readable size.

## Installation

```bash
composer require ixnode/php-size-byte
```

```bash
vendor/bin/php-size-byte -V
```

```bash
php-size-byte 0.1.0 (12-19-2022 01:17:26) - Björn Hempel <bjoern@hempel.li>
```

## Usage

```php
use Ixnode\SizeByte\SizeByte;
```

```php
$sizeHumanReadable = (new SizeByte($fileSize))->getHumanReadable();
```

## License

This tool is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details
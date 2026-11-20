# my-php-app

![CI](https://github.com/TEgor1212/my-php-app/actions/workflows/ci.yml/badge.svg)

PHP app with CI — runs PHP lint + test on push and PR.

A simple PHP application with a CI pipeline that validates syntax and runs PHPUnit tests. A Docker image is built on successful pushes to main.

## Quick Start

```bash
composer install
vendor/bin/phpunit tests/
```
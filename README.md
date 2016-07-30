PHP Quality Assurance Tools [![Build Status](https://travis-ci.org/Webysther/composer-meta-qa.svg?branch=master)](https://travis-ci.org/Webysther/composer-meta-qa) [![License](https://poser.pugx.org/webysther/composer-meta-qa/license)](https://packagist.org/packages/webysther/composer-meta-qa)
==========

This is a composer meta package for installing PHP Quality Assurance Tools with only one dependency, based on [h4cc/phpqatools](https://github.com/h4cc/phpqatools).

Included in this package are:

- [PHPUnit](https://github.com/sebastianbergmann/phpunit): Testing Framework
- [PHPCOV](https://github.com/sebastianbergmann/phpcov): CLI frontend for the [PHP_CodeCoverage](https://github.com/sebastianbergmann/php-code-coverage)
- [Paratest](https://github.com/brianium/paratest): Parallel testing for PHPUnit
- [DbUnit](https://github.com/sebastianbergmann/dbunit): Puts your database into a known state between test runs
- [PHPLOC](https://github.com/sebastianbergmann/phploc): A tool for quickly measuring the size of a PHP project
- [PHPCPD](https://github.com/sebastianbergmann/phpcpd): Copy/Paste Detector
- [PHP_Depend](https://github.com/pdepend/pdepend): Quality of your design in the terms of extensibility, reusability and maintainability
- [PHPMD](https://github.com/phpmd/phpmd): User friendly frontend application for the raw metrics stream measured by PHP Depend
- [PhpMetrics](https://github.com/phpmetrics/PhpMetrics): Static analysis tool, gives metrics about PHP project and classes
- [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer): Detects violations of a defined set of coding standards
- [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer): A tool to automatically fix coding standards issues
- [Security-Checker](https://github.com/sensiolabs/security-checker): Checks if your application uses dependencies with known security vulnerabilities
- [Behat](https://github.com/Behat/Behat): BDD (Behavior Driven Development) framework

Suggest install:

- [Prestissimo](https://github.com/hirak/prestissimo): Composer parallel install plugin

# Usage

The installed tools are available in vendor/bin/ and can be started like this:

```bash
php vendor/bin/phpmd
```

# Installation

To use this package, add it as as "dev" dependency with this command:

```bash
composer require webysther/composer-meta-qa --dev
```

Or modify your composer.json as followed:

```json
require-dev: {
  "webysther/composer-meta-qa": "@stable"
}
```

# Symfony App Pack

A opinionated Symfony pack to get your Symfony application started

## Installation

Ensure you have [Symfony Flex](https://github.com/symfony/flex) installed, otherwise the pack
can not be installed.

Run:
```bash
composer require kocal/symfony-app-pack
```

## Included packages

- `deptrac/deptrac`: Static analysis tool to enforce architectural rules in your PHP projects,
- `kocal/oxc-bundle`: Symfony Bundle to easily download and use Oxlint and Oxfmt (from the Oxc project),
- `kocal/phpstan-symfony-ux`: PHPStan extension that provide quality rules for Symfony UX components,
- `phpstan/phpstan`: Static analysis tool for PHP,
- `phpstan/phpstan-doctrine`: PHPStan extension for Doctrine,
- `phpstan/phpstan-symfony`: PHPStan extension for Symfony,
- `rector/rector`: Tool to automate code refactoring and upgrades in your PHP projects,
- `symplify/easy-coding-standard`: Tool to check and fix coding standards in your PHP code,
- `vincentlanglet/twig-cs-fixer`: Tool to check and fix coding standards in your Twig templates,

## Included files

Included files can be found at the [Symfony Recipes Contrib repository](https://github.com/symfony/recipes-contrib/tree/main/kocal/symfony-app-pack/).

## Why

Because I'm tired of installing and configuring all these tools for every new Symfony project I start (eg. https://github.com/Kocal/Gotta-Catch-Em-All/pull/1).

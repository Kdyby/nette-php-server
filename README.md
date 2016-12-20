Nette PHP Server
================

[![Build Status](https://travis-ci.org/sunfoxcz/nette-php-server.svg?branch=master)](https://travis-ci.org/sunfoxcz/nette-php-server)

Nette console commands for running application in php builtin server.

Requirements
------------

Nette PHP Server requires PHP 5.6 with pcntl extension.

 * [Nette Framework](https://github.com/nette/nette)
 * [Kdyby/Console](https://github.com/kdyby/console)
 * [Symfony/Process](https://github.com/symfony/process)

Installation
------------

The best way to install Nette PHP Server is using [Composer](https://getcomposer.org):

```sh
$ composer require sunfoxcz/nette-php-server
```

You can enable the extension using your neon config.

```yml
extensions:
    console: Kdyby\Console\DI\ConsoleExtension
    server: Sunfox\PhpServer\DI\PhpServerExtension
```
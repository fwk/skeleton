# Fwk\Core Skeleton Application

This is a skeleton Application for [Fwk\Core](https://github.com/fwk/Core).
Install it using [Composer](http://getcomposer.org) to get started:
``` sh
$ php composer.phar create-project fwk/skeleton path/to/install --prefer-dist --dev -o
``` 

Now cd to path/to/install and edit the configuration file:
``` sh
$ cp app/config.ini-dist app/config.ini
``` 

## What's included

* Directory structure and initial configuration 
* Support for [Twig](https://github.com/twig/twig) (via [nitronet/fwk-twig](https://github.com/nitronet/fwk-twig))
* Support for [Assetic](https://github.com/kriswallsmith/assetic) (via [nitronet/fwk-assetic](https://github.com/nitronet/fwk-assetic))

## Cache directory

Assetic and Twig may require a directory to put cache files. By default, it's configured as ```./cache```.
You can initialize this directory by typing:

``` sh
$ mkdir cache && chmod 777 cache
``` 

You can also change this directory path in ```./app/config.ini```.

## Hack on

Now point your browser to your http server: http://localhost/~username/webapp/public/index.php/ and you're set! Happy development :)

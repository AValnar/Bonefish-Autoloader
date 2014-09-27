Bonefish-Autoloader
===================

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/?branch=master)  [![Code Coverage](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/?branch=master)  [![Build Status](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/badges/build.png?b=master)](https://scrutinizer-ci.com/g/AValnar/Bonefish-Autoloader/build-status/master)

Bonefish-Autoloader is a standart PSR-4 Autoloader

Features
========
- Autoload classes with PSR-4 standard

Installation
===========
Please use Composer to install this package.
```shell
$ composer require av/bonefish-autoloader:dev-master
```

Usage
=====
Create a new autoloader instance and use register()
```shell
$autoloader = new \Bonefish\Autoloader\Autoloader();
$autoloader->register();
```

Now you can add Namespaces like this
```shell
// Hello\World\Controller will now search for src/Controller.php
$autoloader->addNamespace('Hello\\World','src');
```



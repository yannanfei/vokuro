Vökuró
======

Phalcon PHP is a web framework delivered as a C extension providing high performance and lower resource consumption.

This is a sample application for the Phalcon PHP Framework. We expect to implement as many features as possible to showcase the framework and its potential.

Please write us if you have any feedback.

Thanks.

NOTE
----
The master branch will always contain the latest stable version. If you wish to check older versions or newer ones currently under development, please switch to the relevant branch.

Required version: >= 1.1.0 B3

Get Started
-----------

#### Requirements

To run this application on your machine, you need at least:

* >= PHP 5.3.9
* Apache Web Server with mod rewrite enabled, and AllowOverride Options (or All) in your httpd.conf
* Latest Phalcon Framework extension installed/enabled

Then you'll need to create the database and initialize schema:

    echo 'CREATE DATABASE vokuro' | mysql -u root
    cat schemas/vokuro.sql | mysql -u root vokuro

Installing Dependencies via Composer
------------------------------------
Install composer in a common location or in your project:

```bash
curl -s http://getcomposer.org/installer | php
```

Run the composer installer:

```bash
cd vokuro
php composer.phar install
```

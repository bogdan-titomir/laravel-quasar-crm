# Laravel 5.7 + Quasar Framework 0.17 (PWA)

This repository is forked from https://github.com/cretueusebiu/laravel-vue-spa. The original repository provides a Laravel-Vue preset based on Bootstrap 4. Instead of Bootstrap, this repository uses the Quasar Framework resulting in applications with a powerful Material UI.

## Build Setup
> rename or copy  .env.example to .env

``` bash
$ cp .env.example .env
```

``` bash
# install php dependencies
$ composer install

# Node.js >= 8.9.0 is required.
$ npm install -g quasar-cli

# install node dependencies
$ npm install

# generate key
$ artisan key:generate

# set privileges to node_modules folder (optional)
#$ chmod -R u+x node_modules/

# first start the back-end (don't use the artisan's serve url in this mode)
$ artisan serve

# then build for development mode
$ quasar dev -m pwa

# OR

# build for production (it'll generate and copy the necessary files)
$ quasar build -m pwa
```

Check out `quasar.conf.js`


## Laravel License
The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Quasar License
Copyright (c) 2016-2017 Razvan Stoenescu
[MIT License](http://en.wikipedia.org/wiki/MIT_License)

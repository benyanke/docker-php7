# PHP 7 docker image

This is a [Docker](http://www.docker.com) image for [PHP 7](http://php.net/) suited to run [Laravel PHP Framework](http://laravel.com/).

An automated build for this repo is available on the [Docker Hub](https://registry.hub.docker.com/u/benyanke/php7/).

This is a fork of [vcarreira/php7](https://github.com/vcarreira/docker-php7).

This includes php 7.1, 7.2, and 7.3, linked to docker tags `7.1`, `7.2`, and `7.3`.

## Related images
This image works is used across the [Docker Laravel](https://github.com/vcarreira/docker-laravel) multi-container solution.

Images used by this:
  - [benyanke/nginx-php7-fpm](https://hub.docker.com/r/benyanke/nginx-php7-fpm) 

## New Packages and Modules

I intend these images to be as flexible as possible, so if you need additional PHP modules, please request it, 
or put in a PR to add it.


## Microsoft SQL Server Driver

These images provide the SQL server driver (both in standard and PDO flavors). The `7.1` and `7.2` images support this, and 
7.3 will support it very soon, as discussed by [@yitam](https://github.com/yitam) in [this thread on the 
repo](https://github.com/Microsoft/msphpsql/issues/847#issuecomment-442923004). There is a dockerfile in `/other` which will 
be used once the PHP SQLSRV driver goes GA for php 7.3.

This driver is still in testing, though will be production ready soon.

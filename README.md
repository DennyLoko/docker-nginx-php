# nginx-php

This is an slightly modified version of the nginx's official image to include by default the option to parse php files using an external php-fpm daemon.

This image was made purely made to do fast tests across multiple servers, so by default it uses an `php` link to the php-fpm container node.

It does not include production-ready configuration and should not be used as such.
